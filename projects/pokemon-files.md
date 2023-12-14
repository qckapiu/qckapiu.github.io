---
layout: project
type: project
image: img/pokemonbank.jpg
title: "Pokemon File IO"
date: 2023-03-08
published: true
labels:
  - file
  - pokemon
  - input
  - output
  - C
summary: "In ICS 212 I developed a program that would read and write Pokemon loaded into a bank onto a file."
---

## Read/Write File
I created the functions readfile and writefile. These functions would access an array that would either be loaded with Pokemon from a file (readfile) or load a file from an array of Pokemon (writefile).

## Driver
This program used a driver to call the functions and execute the code. I created a few test cases by adding various Pokemon by including the species and level. These were added into the array "pokemonbank". Once the array was filled, I would call writefile and overwrite the previous contents with the list of Pokemon. I conducted various cases to make sure that the program worked as intended.

## Output
Below is a screenshot of an example output from the program.
<img class="img-fluid" src="../img/pokemonfileio.png">

## Experience Gained
This project required us to have a solid understanding of the addresses of each variable and how they were linked. If the implementation was done incorrectly, this could lead to the array pointing to a NULL address or even worse it could point to an address of a variable that already exists. This could lead to the program inadvertantly changing variables without your intent.

This project also required us to conduct test cases for our program to ensure that each of our functions were working as intended. I was able to improve on cleaning up my code to ensure that the test cases ran smoothly.
