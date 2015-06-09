## Website Performance Optimization portfolio project

To check the optimizations made open views/pizza at the Github site - https://github.com/WH8248/Project4a

## Items optimized in 
views/js/main.js:
1. In function updatePositions, I moved the scroll calculation (document.body.scrollTop / 1250) out of the for loop to avoid recalulating it over and over when the value stayed the same, and declared var phase outside loop
2. Lowered the for loop that rendered the pizzas that move accors the screen from 200 to 30 to avoid creating pizzas that were not visable.
3. For function changePizzaSizes moved document.querySelectorAll(".randomPizzaContainer").length outside the loop as well as var dx, newwidth
4. (540) var elem moved declare outside loop
5. (475) var pizzasDiv = document.getElementById("randomPizzas") moved outside the for loop to make only 1 DOM call
6. changed document.querySelectorAll to getElementsByClassName

index.html:
1. fixed font error by inlining and updated the style css

css:
For View
to .mover added transform attributes

pizza.html
reduced size of pizzaria image


References used:
Office hours: https://plus.google.com/events/c8eah6f0d0t9eretebpm7dqi0ok?authkey=CKaNhtb0quvqKA
http://i.imgur.com/cI6zwUo.jpg
https://github.com/udacity/fend-office-hours/tree/master/Web%20Optimization/Effective%20Optimizations%20for%2060%20FPS
Github
w3schools
https://css-tricks.com/almanac/properties/t/transform/
https://www.google.com/fonts#UsePlace:use/Collection:Open+Sans