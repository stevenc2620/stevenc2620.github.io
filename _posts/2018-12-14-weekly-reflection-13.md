---
layout: post
title: "Flag Project-In Process" 
date: 2018-12-14
---

```
(define GOLD (make-color 254 204 0))
(define BLUE (make-color 0 106 167 ))
(define SIZE 10)
(define WIDTH (* 16 20))
(define HEIGTH (* 10 20))
(define WIDTH-1 (* 2 10))
(define HEIGTH-1 (* 2 10))
(rectangle WIDTH HEIGTH "solid" BLUE)
(rectangle WIDTH-1 HEIGTH "solid" GOLD)
(rectangle WIDTH HEIGTH-1 "solid" GOLD)
(define SWEEDEN (put-image (rectangle WIDTH-1 HEIGTH "solid" GOLD) 100 100 (put-image (rectangle WIDTH HEIGTH-1 "solid" GOLD) 160 100 (rectangle WIDTH HEIGTH "solid" BLUE))))  
SWEEDEN
``` 
![Flag Image](/Images/Flag.png)

A challenge I had in making the flag was trying to create a code where I'll be able to change one thing and the whole thing would change. I wanted to create a code like that because it would make it easier to change what I want to. For example, in the code I made to create the flag of Sweeden has certain areas there a words with uppercase letters like GOLD, BLUE, WIDTH, and HEIGTH. These words have a code behind it where if a number in it is changed, the image would change as well. This is because the names are in the code to create the flag of Sweeden are connected to the code that defines what they are. 
