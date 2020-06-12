---
layout: project
type: project
image: images/micromouse.jpg
title: Candy Game
permalink: projects/candygame
# All dates must be YYYY-MM-DD format!
date: 2019-12-02
labels:
  - Java
  - Object Oriented Programming
summary: A two-player candy collecting game I developed using the EZJava library.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

This was a the final project I completed for ICS 111. The goal of the game is to avoid the graves and ghosts while collecting the moving candies. The player that collects the most candies while not bumping into the obstacles wins.

The goal of the project was to get students used to working with the skills we learned in class which included file parsing, class structure, private/public member variables and member functions. 

[Library Documentation](http://www2.hawaii.edu/~dylank/ics111/doc/)

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



