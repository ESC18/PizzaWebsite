# Pizza Parlor

#### By Elijah Shawn Cartwright
## Technologies used:
* HTML
* CSS
* GIT
* JS
* Adobe XD
* Chrome & Firefox Web developer tools

## Description of Application:
This web application is a small website where the user can construct and create their own pizzas and generate their own complete order. It can produce as many pizzas as the user wants and allows you to choose from a variety of toppings.

## Setup and installation requirements/guide:
1. Clone the repository _"PizzaWebsite"_ to your device through this link: https://github.com/ESC18/PizzaWebsite
2. Select 'Code' in the repo page.
3. Copy the provided HTTPS Link.
4. Navigate through Git bash to your desired folder to place the project.
5. Do the necessary git commands to initialize the project and then proceed to do: 'git clone https://github.com/ESC18/PizzaWebsite.git'
6. Happy Coding!

## Known Bugs:
* Site is not fully responsive and may struggle with mobile devices.  For Best Results - use a monitor with a 1080x1920 resolution.
* 'Order Now' button isn't always responsive - to fix try hovering away from it and clicking elsewhere on the screen and then trying to click on the button.

## Licensing:
MIT License

Copyright (c) 2023 Elijah Shawn Cartwright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Tests:

Describe: priceTester()

Test: If user selects a small, medium, or large size, it will add the proper amount to the total price.
Code: 
priceTester("small","None","None","None","None","price");
console.log(totalPrice);
Expected Output: Price will be 8.

Test:  If user selects a mozzerella, cheddar, or no cheese, it will add the proper amount to the total price.
Code: 
priceTester("small","Mozzerella","None","None","None","price");
console.log(totalPrice);
Expected Output: Price will be 9.

Test if user selects Pepperroni, Sausage, or no meat, it will add the proper amount to the total price.
Code:
priceTester("small","Mozzerella","Pepperroni","None","None","price");
console.log(totalPrice);
Expected Output: Price will be 11.

Test if user selects Pineapple, Tomato, or no first topping, it will add the proper amount to the total price.
Code:
priceTester("small","Mozzerella","Pepperroni","Pineapple","None","price");
console.log(totalPrice);
Expected Output: Price will be 12.

Test if user selects Olive, Pepper, or no second topping, it will add the proper amount to the total price.
Code:
priceTester("small","Mozzerella","Pepperroni","Pineapple","Olive","price");
console.log(totalPrice);
Expected Output: Price will be 14.