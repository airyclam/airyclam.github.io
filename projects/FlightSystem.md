---
layout: project
type: project
image: images/plane-square.jpg
title: Quick Trips
permalink: projects/vacay
# All dates must be YYYY-MM-DD format!
date: 2020-05-17
labels:
  - Java
  - Object Oriented Programming
  - Data Structures
  
summary: A flight reservation system I made using array lists, linked lists, and maps.
---

<img class="ui medium right floated rounded image" src="../images/plane.jpg">

This is an implementation of a flight reservation system I made for ICS 211. The user navigates through a text-based menu to perform a variety of tasks such as:
* Create a new passenger
* Edit information for an existing passenger
* Display all passenger information based on name
* Display all passenger information based on number of segments flown
* Book a reservation
    * If there's no seats available on the flight, add the passenger to the waitlist
* Cancel a reservation
    * If there's a waitlist, add passengers in order of the waitlist
* Display all flights with flight details

In this project I gained experience working with various kinds of data structures and implementing them in a practical setting. The most challenging part for me was figuring out how to structure the waitlist. I envisioned one linked list with all the names reserving a flight so that removing one name would move the others up, but I wasn't sure exactly how to separate the top 5 as the passengers and the rest as the waitlist. I ended up making a for loop in the main class as shown below.
```java
// Prints out Passenger List and Waitlist
for(int i = 0; i < flightMap.get(flightNumber).getSize(); i++) { 
    if (i<5) {
        System.out.println("Passenger"+ Integer.sum(i,1) + ". " + flightMap.get(flightNumber).output(i));
    } else {
        System.out.println("Waitlist"+ Integer.sum(i,-4) + ". " + flightMap.get(flightNumber).output(i));
    }
```
Having this loop in the main class ensures that the passenger and waitlist are up-to-date when called. One disadvantage of this setup is that if I wanted to call all the names in the waitlist, I would need to make an extra 5 iterations before getting access to the first name of the waitlist. An extra 5 iterations doesn't make very much of a difference, however. Also, since I only ever call the waitlist with the passenger list, it's not a waste.

If I did need them to be called separately, an arraylist would allow me to do this. However, since a waitlist is a set of data that's constantly having names removed from various positions and names tacked on at the end, I decided to use a linked list.

Overall, this project was a very good experience. 

Source: <a href="https://github.com/airyclam/FlightSystem"><i class="large github icon"></i>airyclam/FlightSystem</a>
