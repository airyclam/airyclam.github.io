---
layout: project
type: project
image: images/vacay-square.png
title: Smile Travel
permalink: projects/vacay
# All dates must be YYYY-MM-DD format!
date: 2020-05-17
labels:
  - Java
  - Object Oriented Programming
  - Data Structures
  
summary: A flight reservation system I made using array lists, linked lists, and maps.
---

<img class="ui medium right floated rounded image" src="../images/vacay-home-page.png">

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

In this project I gained experience working with various kinds of data structures and implementing them in a practical setting. The most challenging part for me was figuring out how to structure the waitlist. I envisioned one big priority queue with all the names reserving a flight so that removing one name would move the others up, but I wasn't sure exactly how to separate the top 5 as the passengers and the rest as the waitlist. I ended up making a for loop in the main class so that the list of passengers is up-to-date when called.
 
Source: <a href="https://github.com/airyclam/FlightSystem"><i class="large github icon"></i>airyclam/FlightSystem</a>
