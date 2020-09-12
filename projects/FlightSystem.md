---
layout: project
type: project
image: images/plane-square.jpg
title: Quick Trips
permalink: projects/quicktrips
# All dates must be YYYY-MM-DD format!
date: 2020-05-17
labels:
  - Java
  - Object Oriented Programming
  - Data Structures
  
summary: A flight reservation system I made using array lists, linked lists, and maps.
---

<img class="ui medium right floated rounded image" src="../images/plane.jpg">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This is a flight reservation system I implemented for ICS 211, the second programming class in the computer science series at UH Manoa. The user navigates through a text-based menu to perform a variety of tasks such as:
* Create a new passenger
* Edit information for an existing passenger
* Display all passenger information based on name
* Display all passenger information based on number of segments flown
* Book a reservation
    * If there's no seats available on the flight, add the passenger to the waitlist
* Cancel a reservation
    * If there's a waitlist, add passengers in order of the waitlist
* Display all flights with flight details

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this project I gained experience working with various kinds of data structures such as maps, array lists, linked lists, as well as implementing them in a practical setting.


The most challenging part for me was figuring out how to structure the waitlist. I envisioned one linked list with all the names reserving a flight so that removing one name would move the others up, but I wasn't sure exactly how to separate the top 5 as the passengers and the rest as the waitlist. I ended up making a for loop that I used in the cancelReservation() and printFlights() functions. 
```java
// Prints out Passenger List and Waitlist
for(int i = 0; i < flightMap.get(flightNumber).getSize(); i++) { 
    if (i<5) {
        System.out.println("Passenger"+ Integer.sum(i,1) + ". " + flightMap.get(flightNumber).output(i));
    } else {
        System.out.println("Waitlist"+ Integer.sum(i,-4) + ". " + flightMap.get(flightNumber).output(i));
    }
```
Basically, the flightMap contains a key (flightNumber) and a value which is the linked list of names registered for that specific flight. This for loop iterates through the number of names in the list and prints out the first five as being passengers and the rest as waitlisted.

I think if I were to work on this project with my current knowledge, at the very least I would put this for loop into a separate function so I'm not copy pasting this entire for loop into different functions every time I need the waitlist and passenger list. 

Overall, I think this project gave me a very good basic understanding of how to use data structures to store information. I hope to use this information in my future classes and projects.

Click here to take a look at the complete code: <a href="https://github.com/airyclam/FlightSystem"><i class="large github icon"></i>airyclam/FlightSystem</a>
