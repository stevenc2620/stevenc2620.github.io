---
layout: post
title: weeekly reflection
date: 2018-11-15
---

In this week what we did was decide how we can demostrate real-life examples as a code. For example, a problem we had was to figure out how to show a rocket blasting off. There were a lot of ideas such as drawing a visuale, copying an image address and defining it, using posn to find its location. Also, we discussed how the contract, examples, and definitions relate to each other. One way these all connect is that each one is needed for the other. The contract helps write the exameple by knowing what the example is supposed to contain and a definition will only work if an example is present. For example a contract can be ```:triangle: Number String String -> Image``` and an example of this contract is ``` (triangle 50 "solid" "green")```. the contract helps one know what can go into the function to work and give what you want, a solid colored green the size of 50. Defining the example makes it easier to get what you want like ```(define (gt size) (triangle size "solid" "green"))```. This allows you to chnage the size without wrioting an exmaple everytime and just using ```(gt size)```.    
