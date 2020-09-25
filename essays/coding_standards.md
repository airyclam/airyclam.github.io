---
layout: essay
type: essay
title: Those Darn Red Lines
# All dates must be YYYY-MM-DD format!
date: 2020-09-24
labels:
  - Javascript
  - Learning
  
---

## Importance of Readable Code

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This past summer, I started working at Pacific Health Analytics Collaborative (PHAC), a research group that uses applied analytics to drive public health policy in Hawaii. Under this group, I'm currently assigned to a project to automate the creation of the yearly [epidemiological profiles](https://health.hawaii.gov/substance-abuse/files/2019/06/Alcohol_2018_Hawaii_State_Epidemiologic_Profile.pdf) on drug and alcohol abuse. To create these profiles, data from various national surveys are compiled.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Someone on the team had previously fiddled with some of the survey data and graciously let me and my partner see some of the scripts he wrote as a reference. Right when I opened the scripts, I was surprised at how professional everything looked. There were headers for every function with ```@param``` and ```@return``` descriptions, and everything was neatly indented. Even though the original author was doing this alone as a side project, it was written so that pretty much anyone with light coding experience could understand. I want to write code like that.

## ESLint

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In my software engineering class we are using a node module called ESLint to make sure our code follows the coding standards set by our professor. Although seeing all those red lines in my code gets really annoying, I think ESLint has been really helpful in developing good habits while writing my code. A lot of the time, there are red lines on things that I never even knew were "wrong" until I started using ESLint. For example, when creating an empty array to add values into, I was surprised to see that I got an error when I used ```let array = [];```. Thinking back to my program structure class in C, I remembered that an array is technically just a pointer to the first address, which wouldn't change even when the elements in the array does. I guess this is probably what our professor meant when he told us that ESLint would teach us more about the language as well. I hope that by the end of this semester, I'll have learned from the different style errors I keep seeing pop up in my IDE, and be able to write clean code naturally.



