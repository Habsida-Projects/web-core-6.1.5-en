## Create Responsive layout

You need to create an adaptive page based on a figma layout.

### Materials

1) [Layout Design](https://www.figma.com/file/ShRyWXLHE6S2tI293PbuG0/6.1.5-Final_layout-en?type=design&mode=design&t=6QowXpPUHH43Hu7A-1)
2) Font family: Roboto
3) Colors - see layout
4) Content texts - you can use texts from the layout and/or "lorem ipsum"
5) Icons and images - export from figma

### Interactive

1) The mobile menu should open when you click on the “burger” button on the left in the header. On a tablet, the menu closes either when you press a button or when you click on a “blurred” area. The menu itself should not be duplicated in the code - change it by positioning..
2) When you click "Show all" a more complete list should open (use the same logos/texts)
3) For sliders we use [this module](https://swiperjs.com/). There is no need to remove/add the slider during resize - see whether to initiate the slider or not depending on the initial screen width.
4) By clicking on the button with the handset, the “request a call” modal opens.
5) By clicking on the button with the message, the “feedback” modal opens.

### Requirements

1) We take a simple webpack assembly as a basis. [from here](https://github.com/jm-program/webpack-static-template). Assembly usage manual - [here](https://gist.github.com/didolf/b2fcdab713265eee5852221ebf5df7d5)
2) Browser Support - Latest versions of Safari, Chrome, Firefox.
3) Without using CSS frameworks and without jQuery.
4) Between the specified resolutions (320, 768, 1440), everything should look adequate, and nothing should break. On larger resolutions, center the page. The arrangement of blocks is up to you. Keep in mind that desktops nowadays typically start from 1366px in width (budget laptops).
5) All styles should follow BEM (Block, Element, Modifier) naming convention - two dashes: `block-name__elem-name--mod-name--mod-val`
6) We use SCSS, separate styles into different files based on logical blocks, and store colors in variables. For styling elements using BEM, utilize the nesting functionality..
7) The result should be provided in the form of a repository on GitHub, along with links to GitHub Pages.
8) There should be no compiled .css in the master branch, only sources
