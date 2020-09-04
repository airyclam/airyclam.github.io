---
layout: essay
type: essay
title: Upping My Game with Javascript
# All dates must be YYYY-MM-DD format!
date: 2020-09-02
labels:
  - Javascript
  - Learning
  
---

## Athletic Software Engineering

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Before taking software engineering at UH Manoa, I had never worked with javascript. I knew it was used to implement interactivity on web pages, but that was as much as I knew about the language. After doing a few homework and classwork exercises in javascript, I have realized how versatile it is. I no longer have to worry about data types and function outputs being consistent. Also, with so many useful functions in the standard library, I can complete a wide range of tasks with just a few lines of code. 


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The efficiency of javascript code makes the language especially suitable for Dr. Philip Johnson's [athletic software engineering](https://philipmjohnson.org/essays/athletic-software-engineering.html) teaching model, a model focused on teaching students to code quickly.

<blockquote> <em>  [Athletic Software Engineering] is a pedagogy in which some or all of the
             course is organized into a series of skills to be acquired. For
             each skill, students are given “workouts” (practice problems)
             along with videos showing the instructor performing each
             workout correctly, quickly, with verbal explanations of their
             choice of tools and design techniques as they apply them.
             Students are advised to repeat the workout until they can
             complete it not just correctly, but in approximately the same
             time as the instructor. </em> </blockquote>   
<em> Philip Johnson, Dan Port, Emily Hill [(2016)](http://cs.drew.edu/~emhill/papers/CSEET16.pdf) </em> 


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "Athletic software engineering" takes a page from sport pedagogy. In order to get good, you need to practice. Back in high school when I was training for varsity tennis tryouts, I would spend hours a day doing drills with my coach multiple times a week. We would practice all the different strokes in multiple different scenarios to ensure that I was ready for game day. Even after I got onto the varsity team, it just meant even more practicing. Nothing beats repetition when learning a new skill, and coding is no different. Sure the opponent / project may be different each time, but you'll always be relying on your fundamentals to win.  


## First Impressions
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Today, I experienced my first in-class "Workout of the Day". We were assigned into pairs to create a javascript function that would take a blackjack hand and calculate the point value. This function would return the point value if less than 21, return "Blackjack!" if exactly 21, or return "Bust!" if greater than 21. We had 15 minutes to implement this function, but it honestly felt more like 5 minutes. Although the assignment was pretty straightforward, I got caught into snags really quickly. 
```javascript
1 for (let i = 0; i < hand.length; i++) {
2     if (hand[i] == "T" | "K" | "Q" | "J" ) {
3         counter += 10;
4     } else {
5         counter += hand[i];
6     }
7 }
```
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This is what I wrote on my first attempt. After testing with print statements I realized that line 5 wasn't going to work because the numbers were being read in as a string. To solve this, I had to either make cases for each number or make some sort of dictionary. I was running out of time and I didn't feel comfortable enough with javascript yet to know how to make a dictionary (which I found out later is just an object with only key value pairs). My partner, Justin, was working on a solution with switch cases which seemed to be working, so we ended up hacking a gross 13 case switch statement in the last minute.


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Being on a timer is definitely stressful, but also really exciting. Coding assignments in my other computer science classes were always on weekly cycles, where I would meticulously make sure my code was up to the teacher's standards in terms of style and functionality. Going from weeklong due dates to 15 minute due dates means I can only implement what I immediately know off the top of my head. This is great feedback because it also tells me what I'm lacking in terms of coding "tools". With WODS I can objectively examine my skillset and determine what areas I need to develop. I'm excited to see where I can take my "game" with athletic software engineering.

