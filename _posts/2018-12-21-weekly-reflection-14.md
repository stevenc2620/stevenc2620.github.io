---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _Sweeden_ by _Steven C._


## Describe your program

The country's flag I worked on was the flag of Sweeden. 

I probably would expect a 3 as a grade because I showed effort in writing a funciton that would change because of one thing. Also, because my flag is scaleable where the ratio of the stripes and the rest of my flag is placed accurately.  

## Current output

* * *
![FlagV2](/Images/FlagV2.png)
* * *

## Describe your process.

Something that helped me was when Mr. Allata showed what we could do to create a function that would chnage if we chnage just one number. For example, instead of changing a bunch of things, we could connect all the ducntions to one function definiton so that function will chnage everything for us. 

* * *

## Explain your code.

```
(define size 20)
(define width (* 16 size))
(define heigth (* 10 size))
(define stripe-width (* 1/8 width))
(define stripe-heigth (* 1/5 heigth))
```
The first function defines the size in general. The second and third both define the height and the width of the flag's base. What it would do is that it takes in the size and muliplies it by 16 for width and 10 for the heigth. If we change the size then the heihth and the width will also chnage based on the number defined by size. The last two functions define the size for the height and the width. The width multiplies 1/8 by the original width while the heigth multiplies 1/5 and the original heigth. This works for me since it'll be easier to scale because if I chnage size to a different number the heigth and the width will also change. The width and the heigth chnaging will also make the stripe-width and the stripe-heigth chnage as well. 



* * *

```
(define gold (make-color 254 204 0))
(define blue (make-color 0 106 167 ))
```
These two functions will allow me to use the name gold and blue to accurately use the corret colors of the Sweeden flag. Using the funciton make-color allows me to use the numbers to create the colors that the numbers would create. Defining it will make it easier to just write the name (either gold or blue) to then have the color made inputed to the image.  

* * *



## Program code

```
;color
(define gold (make-color 254 204 0))
(define blue (make-color 0 106 167 ))
;base 16:10/ size 2
(define size 20)
(define width (* 16 size))
(define heigth (* 10 size))
(rectangle width heigth "solid" blue)
;stripes 
(define stripe-width (* 1/8 width))
(define stripe-heigth (* 1/5 heigth))
(rectangle width stripe-heigth "solid" gold)
(rectangle stripe-width heigth "solid" gold)
;flag output
(define sweeden (put-image (rectangle stripe-width heigth "solid" gold) 100 100 (put-image (rectangle width stripe-heigth "solid" gold) 160 100 (rectangle width heigth "solid" blue))))  
sweeden

```
