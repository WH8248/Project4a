## Website Performance Optimization portfolio project

To check the optimizations made open views/pizza at the Github site - https://github.com/WH8248/Project4a

## Items optimized in views/js/main.js
1) In function updatePositions, I moved the scroll calculation (document.body.scrollTop / 1250) out of the for loop to avoid recalulating it over and over when the value stayed the same
2) Lowered the for loop that rendered the pizzas that move accors the screen from 200 to 30 to avoid creating pizzas that were not visable.

References used:
Office hours: https://plus.google.com/events/c8eah6f0d0t9eretebpm7dqi0ok?authkey=CKaNhtb0quvqKA
http://i.imgur.com/cI6zwUo.jpg
https://github.com/udacity/fend-office-hours/tree/master/Web%20Optimization/Effective%20Optimizations%20for%2060%20FPS
Github