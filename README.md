## Website Performance Optimization portfolio project

Optimized online portfolio for speed! In particular, optimized the critical rendering path and made this page render as quickly as possible.
## How to run
Open index.html

Optimizations done : 
#### Part 1: Optimized PageSpeed Insights score for index.html
1. Optimized Images
2. Minified JavaScript
3. Minified CSS
4. Inline CSS styling

#### Part 2: Optimized Frames per Second in pizza.html
Modified views/js/main.js in the following ways:
1. Replaced querySelectorAll with getElementsByClassName for better performance
2. Reduced the amount of animated pizzas from 200 to 30
3. Moved calculation of "dx" and "newwidth" outside the for loop in function "changePizzaSizes" 
4. Assigned all the elements from "document.getElementsByClassName("randomPizzaContainer")"" to a variable "pizzaContainers"
5. replaced "querySelector(..)" with "getElementById(..)"
