# Website Performance Optimization Portfolio Project

Website Performace Optimization Portfolio Project is an optimized webpage of Cameron's portfolio website.

## Installation

Clone the GitHub repository

	`$ git clone http://mgysel.github.io/`

Open the index.html file in the project folder, which will take you to the portfolio website.

## Optimizations

### views/js/main.js

1. The number of document queries and for loop calculations within resizePizzas() was reduced.
2. faster document selectors were used throughout, such as getElementById and getElementByClassName()
3. For loop calculations within updatePositions() were reduced.
4. The number of background pizzas was reduced.

### pizza.html
1. Image sizes were optimized
2. CSS files were minified and inlined in the header.