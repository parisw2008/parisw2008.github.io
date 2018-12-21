---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _sweden_by paris wright

## Describe your program

-   What country did you design for? 
-   What grade do you expect? 

<!--- I am designing the flag for sweden. I expect at least a apprentice.

## Current output

-   

* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

- I had to ask a lot of questions to finish this program. I had to ask what put image was and how i could put three images into one image. Really, my biggest challenge was trying to put three images in one and not get frustrated every few minutes because computer science is the hardest subject ive ever did.



## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```  (define base (scale .4(rectangle width height "solid" "blue")))
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
I was writing this function to program the base of the flag( the image where the other images will be put on). i wrote scale *4 because the flag was very small for sum reason, i never figured out why to be honest. the rest of the function is just a contract being written to describe the base and how it will look.


## Program code

```
(define size 100)
(define width(* 15 size))
(define height (* 10 size))
(define yellow-height (* height 1/5))
(define yellow-width (* height 1/6))
(define base (scale .4(rectangle width height "solid" "blue")))
(define yellow-stripe (scale .4(rectangle width yellow-height "solid" "yellow")))
(put-image yellow-stripe 300 200 (put-image (rectangle 100 800 "solid" "yellow") 200 30 base))

```
