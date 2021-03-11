---
title: 5.A Loops Investigate
unit: Lists, Loops, and Traversals
order: 6
is_assignment: true
objectives:
  - Read programs that use for loops
  - Understand the parts of a for loop
  - Update the Boolean expression in a for loop to change how many times the loop runs
dropbox:
  title: 5.A Unit 5 Digital Journal
  url: https://kingsport.instructure.com/courses/21067/discussion_topics/36025
---

## Warm-Up

<div style="border: 1px solid #ccc; border-radius: 15px; padding: 0.5em 2em 1em 2em;">
  <p class="text-xl"><strong>🤔 Reflect:</strong> Imagine you want to build an app for reminders. What information do you think would be stored in a list?Imagine you are interested in finding out how much time it takes on average to walk from one end of your school to the next. You've decided to figure this out on your lunch break, and are able to complete the walk 20 times. What would your algorithm look like? Where could a loop show up?</p>
</div>

A loop helps simplify code. Let's investigate how this looks in two different apps.

## Loops Investigate

<div style="border: 1px solid #ccc; border-radius: 15px; padding: 0.5em 2em 1em 2em;">
  <p class="text-xl"><strong>🤔 Reflect:</strong> The first app we are going to investigate uses a loops in a simulation. What is a simulation? Why are they useful?</p>
</div>

Some examples of simulations are flight simulators which allows you to practice flying without damaging yourself or a real plane or a city building game where you can play with tweaking multiple values in the economy without real consequences.

These examples demonstrate the process of developing an abstract simulation where the specific details have been removed, or the functionality simplified.

While simulations are a useful way to model the real-world, we also need to be constantly on the lookout for bias in the real-world elements that are actually included in the simulation.

Today, we are going to look at a simple simulation.

Simulations can be helpful to run when it would take a long time or it would be too impractical to do something physically. For example, what if we wanted to see the results of a coin flip that we flipped a million times? That would take a long time to perform ourselves, but a computer can run that simulation much quicker. Let's look at an app that does just that.

### Level 2 - Coin Flipper App

[Open Code Studio, Lesson 6 Level 2](https://studio.code.org/s/csp5-2020/stage/6/puzzle/2){: style="border: 1px solid #ccc; border-radius: 5px; padding: 8px 10px; background: #efefef;" target="\_blank"}

Discuss the following:

- What information does the user input?
- How does the app process that information?
- What is being repeated?
- Where is there an opportunity to use a loop?
- What information does the app output?

### Level 3 - Coin Flipper App

Run the program for 10 coin flips, 100 coin flips, and 10,000 coin flips. When do you notice it taking longer? On what lines of code is the program using a loop? Which lines of code decide how many times to flip the coin? \* What does the ++ command seem to do?

[Open Code Studio, Lesson 6 Level 3](https://studio.code.org/s/csp5-2020/stage/6/puzzle/3){: style="border: 1px solid #ccc; border-radius: 5px; padding: 8px 10px; background: #efefef;" target="\_blank"}

## Level 4 - Font Tester App

Find the four different for loops in the program. What do they each do?

Then take a look at the names of the screen elements in Design Mode. Then navigate back to the code. How is "text" + i used? How does it evaluate with each round of the loop?

[Open Code Studio, Lesson 6 Level 4](https://studio.code.org/s/csp5-2020/stage/6/puzzle/4){: style="border: 1px solid #ccc; border-radius: 5px; padding: 8px 10px; background: #efefef;" target="\_blank"}

**Do This:**

- What happens if you change the text box variable names?
- Try changing them from "text0", "text1", etc. to "textbox0", "textbox1", etc.
- Navigate back to the code. What do you need to change in the code for the program to still work?

**Do This:**

- What happens if you change the Boolean expression i < 5 in the for loops?
- Change all the Boolean expressions to one of the options below, run the program, and discuss. Then move to the next option and repeat:
  - i < 4
  - i < 3
  - i <=4

## Wrap-Up

Let's review parts of a loop.

<div style="border: 1px solid #ccc; border-radius: 15px; padding: 0.5em 2em 1em 2em; margin: 2em 0 0 0;">
  <p class="text-xl"><strong>✍️ Journal:</strong></p> <p>What aspects of working with for loops do you feel like clicked today? What do you still feel like you have trouble with?</p>
  <p>When breaking a problem down, you often encounter elements that you want to use repeatedly in your code. Sometimes it's appropriate to write a new function; at other times it's appropriate to write a loop. There is no hard-and-fast rule as to which is better, but what do you think? What kinds of circumstances would lead you to writing a function versus using a loop?</p>
</div>

Working with for loops can be a little tricky. We'll have more opportunities to practice combining loops and lists together to make even more powerful apps.
