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
(define SWEEDEN (put-image (rectangle WIDTH-1 HEIGTH "solid" GOLD) 100 100 
(put-image (rectangle WIDTH HEIGTH-1 "solid" GOLD) 160 100 (rectangle WIDTH HEIGTH "solid" BLUE))))  
SWEEDEN
``` 
![Flag Image](/Images/Flag.png)

A challenge I had in making the flag was trying to create a code where I'll be able to change one thing and the whole thing would change. I wanted to create a code like that because it would make it easier to change what I want to. Later on in the week I restarted because I was confused in how to input it to the codes I already had. Restarting helped because I knew what I wanted. For example, in my code I have a string called BLUE. BLUE has its own code ```(define BLUE (make-color 0 106 167 ))```. What this code does it that using the name BLUE in a code will make the color the color I put it to be. If one numbee is to be changed the color will change. 

Next week, something I'll be working on is my flag collage that I haven't finished. I messed up and never finished so I'll finish it. Another thing I could work on is understanding the relationship of the proportions in the flag. It's important becuase it makes me sure that the flag is scaleable. 
