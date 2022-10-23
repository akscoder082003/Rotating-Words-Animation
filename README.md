# Rotating-Words-Animation

The main focus of this project is how to showcase your profession or skills in a portfolio.
There are many different ways to do it, but my idea is to rotate the words (UI Designer, UX Designer, Web Developer,etc) in a fixed place.

Here i have used ->
## **animation property:** 

This specify the animation duration property, otherwise the duration is 0, and will never be played.

Property names that are prefixed with --, represent custom properties that contain a value that can be used in other declarations using the var() function.

## **var() function:**

var() functiom is used to insert the values of a CSS variable.

## **tranform-origin property:**

The transform-origin property allows you to change the position of transformed elements.

2D transformations can change the x-axis and y-axis of an element. 
3D transformations can also change the z-axis of an element.

## **@keyframes rule:**

The @keyframes rule specifies the animation code.

The syntax is->
**@keyframes animationname{keyframes-selector{css-styles;}}**

For example:> **@keyframes animation{from {top: 0px;}
                                   to {top: 100px;}}**
                                   
('from' is 0% and 'to' is 100%)
We can also set that, at what percent what will happen.

Note: Just remember that whatever percent you takes it always related to time you've taken. So you've to set accordingly.

I have selected total of 24s of animation.
5%, 10%, 20%, 25% this all are related to time 24s, it means while the rotation of words at what percent the style changes.


## **opacity:**

opacity 1 is default (fully visible), if you want to show less visible text or image, 
so you have to decrease the value, for example(0.2, 0.5, etc).

## **tranform property:**

I have also used tranform property, to translateY-axis and rotate the words.
