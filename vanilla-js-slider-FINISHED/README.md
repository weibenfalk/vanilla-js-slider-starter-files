# Slider-Carousel---Lightweight-in-Vanilla-JS-ES6-
A lightweight slider with some ES6 syntax and CSS animations

There´s too many sliders out there that are great but have to many functions etc. 
I decided to do my own lightweight slider that´s independent and written completely in Vanilla JS.

There´s also many sliders that just fade the images up and down. I wanted a slider carousel that actually slides the images in and out. To accomplish that my approach is to keep track of the nearest two slides in both directions relative to the active slide and apply different animation classes. The classes do the CSS animation either to the left or right of the screen.

TODO: Implement some kind of navigation dots

I also tried out using the Flexbox for centering vertical and the "object-fit" in the CSS for covering.
It´s also possible to add an overlay text over the slides and be styled to your own likings.
