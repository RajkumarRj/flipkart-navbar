# flipkart-navbar

Hosted link: https://rajkumarrj.github.io/flipkart-navbar/


![Uploading image.png…]()


Flipkart Navbar
This is a simplified representation of a navigation bar similar to Flipkart's website, built using HTML and CSS. 
Below, you'll find a detailed explanation of each part of the HTML structure and the corresponding CSS properties used.

Flipkart Navbar

Table of Contents
Overview
HTML Structure
CSS Styling
Usage
License
Overview
This project demonstrates the creation of a responsive navigation bar that includes a logo, search bar,
login button, menu items, and a cart icon, closely resembling the layout used by Flipkart.

HTML Structure
The HTML structure is organized as follows:

The <header> element represents the header of the webpage.
Inside the <header>, there is a <nav> element containing an unordered list (<ul>) of navigation items (<li>).
The logo is displayed using an <img> element with the id "logo."
The search bar consists of an <input> element with a placeholder for searching.
The "Login" button is created with an <input> element of type "submit."
Other menu items are listed as text inside <li> elements.
The cart icon is displayed using an <img> element with the id "cart."
CSS Styling
The CSS properties used for styling the HTML structure are as follows:

margin: 0; padding: 0; box-sizing: border-box;: This CSS rule resets margin and padding to zero and sets the box-sizing 
property to "border-box" for consistent box model behavior.

header: Sets the background color of the header to #047BD5, which is a shade of blue.

nav #logo: Styles the logo image by specifying its width, height, and vertical alignment.

li: Removes the default list styling for list items.

nav: Styles the navigation bar with specific width, height, margin, text color, font size, and font weight.

nav>ul: Configures the layout of the unordered list within the navigation bar, using flexbox for spacing and alignment.

input[type="text"]: Styles the search input field with a specific width, height, and negative margin to adjust its position.

input[type="submit"]: Styles the "Login" button with specific width, height, color, font size, and font weight.

#cart: Styles the cart icon by specifying its width, height, and vertical alignment.

.head: Styles the main content of the header, setting its background color, display properties, and alignment.

.item img: Styles the images within menu items, specifying their width and height.

.item: Styles each menu item with text alignment and font weight.

#arrow: Styles the down arrow icon used in some menu items by specifying its width, height, and vertical alignment.
