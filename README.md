# Color and Opacity

#### The amount of transparency for some color or all to be visible through a covering element.

##### Opacity can be used on RBA, HSL and HEX color schemes. 
##### In CSS example would be:
###### *pElement {*
######     *color: rgb(255, 0, 0);*    --> red
######     *color: hsl(120, 100%, 50%);*    --> green
######  *}*

##### Adding Opacity to RBG adn HSL color schemes. We first convert it to RGBA and HSLA:
###### *pElement {*
######     *color: rgba(255, 0, 0, 0.6);*    --> red with opacity
######     *color: hsla(120, 100%, 50%, 0.3);*    --> green with opacity
######  *}*

##### Adding Opacity to RBG adn HSL color schemes. We first convert it to RGBA and HSLA:
---
###### *pElement {*
######     *color: rgba(255, 0, 0, 0.6);*    --> red with opacity
######     *color: hsla(120, 100%, 50%, 0.3);*    --> green with opacity
######  *}*

The first 3 values work the same in the individual color schemes the last value is for the ALPHA - a.





