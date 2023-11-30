---
layout: essay
type: essay
title: "Gotta Solve Them All"
# All dates must be YYYY-MM-DD format!
date: 2023-11-29
published: true
labels:
  - design patterns
  - website design
  - UI
---

Solving problems is trickiest on the first attempt. Perhaps you decide to brute force it and run into a number of unforeseen issues. Or you may attempt to take the time to prep and methodically handle the problem. But once you’ve solved the problem, it becomes substantially easier to deal with it when it comes up again. In software engineering, design patterns are like a template, a reusable solution that you can apply if the conditions are met.

## Designing for function and aesthetics

It is far more efficient to write code that can solve common problems rather than attempting to solve each problem individually. When you design a website that incorporates elements that store data, it is typically useful to find a way to display the information. For the project I’ve worked on recently, our group has used cards to display the various information from vendors and their corresponding menu items. Instead of creating multiple different methods to display the information, we were able to condense the code to just a couple JavaScript files. This allowed us to save a significant amount of time as well as creating a uniform design throughout our various web pages.

<img width="1000px" class="rounded" src="../img/card-image.png">

Design patterns are not limited to improving the program’s code, it can be created to deal with the actual design of the application you’re creating. The moment a website is first created, you start out with a blank sheet. The website designer is left with the task to create a cohesive and eye-catching design, as well as making it functional. I’ve used techniques such as color blocking and consistent styling in order to accomplish this.

<img width="1000px" class="rounded" src="../img/design-1.png">

<img width="1000px" class="rounded" src="../img/design-2.png">

## A single solution can't solve every problem

If a design pattern is too general, it is possible for the program to incorrectly assume that two different problems can be solved with the same solution. While this will lead to errors, I believe that it is a fundamental step in improving the program. Running into these types of bugs will force the programmer to refine their design pattern, allowing for more efficiency and cleaner code in return.

During an in-class WOD (an assignment graded on an all or nothing point system), I was tasked to recreate a website based off a currently existing one. The template that I worked off of was for a website that had small margins, even for the full width picture. I attempted to create the website with the old template which created margins that I could not get rid of. I ended up getting 0 points because I couldn't realize in time that there was a non-fluid container on the page that imported the various pages. While I ultimately figure out how to solve the similar but different problem, this did lead to me losing 100 points.

## References
- [https://sourcemaking.com/design_patterns](https://sourcemaking.com/design_patterns)
- [https://www.geeksforgeeks.org/introduction-to-pattern-designing/](https://www.geeksforgeeks.org/introduction-to-pattern-designing/)



