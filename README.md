# Flex-Navbar
A lightweight and responsive navbar using Jquery and CSS flexbox. This was made because sometimes I would like to implement a navbar without any extra Bootstrap weight. From this starter, I can modify the navigation to create any unique design I need.

# See it in action
https://earltilluck.github.io/Flex-Navbar/

## Usage.
Copy code from navbar.html into new project, Modify the html and css code to suit your needs.

## How it works.
For the normal view, the .nav-item div (with menu content) is set to position static and resides in the nav parent which is a flexbox container. 
For the collapsed view, the position is set to fixed and moved offscreen to the right. 
When the toggle button is clicked, Jquery is used to move the position inward onto the screen. 
An overlay is also made visible under the menu but above the content which prevents interaction while the menu is visible. 
If the user clicks anywhere on the overlay, the menu closes.
Media queries are used to hide the toggle button and restyle the links for each viewport size.
Animation is done via CSS transition property.

## Caveats
* Works best if body has no margin or padding.
* If only one navigation is present onscreen, it would be better to use #id instead of classnames for some elements.