---
layout: project
type: project
image: images/micromouse.jpg
title: Get Milk!
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2020-11-29
labels:
  - ICS 111
  - Eclipse
  - Java
summary: A text-based adventure game I developed for ICS 111
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

For ICS 111, my professor decided that it would be fun to have his students create a game as a final project for the semester. The kind of game was up to the student; as long as you could create the game within two weeks, you were allowed to choose whatever genre you wanted. Originally, I wanted to create a turn-based RPG for the project; but the more I thought about it, I realized it was a terrible idea considering that I came into this class knowing absolutely nothing about coding beforehand. So, I decided that a text-based adventure game would be more suitable for someone with my experience. I titled the game "Get Milk!" and the your objective is to get milk for your cereal. It plays out like any typical text-based adventure, and there's six endings. Everyone had to work independently, there weren't any groups.

Since this was an independent project, I was in charge of everything in the making of this game. Namely, I was in charge of coding everything and creating the game assets. Coding the game was fairly simple; I just made it so that all the relevant information was shown to the player, and that the player could click on a button to choose their next course of action. The game assets consisted of drawn visuals for both the scenes and the buttons (yes, the buttons themselves were drawn pngs). Most of the visuals were drawn on MS Paint with a mouse.

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



