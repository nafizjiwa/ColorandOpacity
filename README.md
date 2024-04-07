# Color and Opacity

#### The amount of transparency for some color or all to be visible through a covering element.

##### Opacity can be used on RBA, HSL and HEX color schemes. 
##### In CSS example would be:
###### *pElement {*
######     *color: rgb(255, 0, 0);*    --> red (RBA)
######     *color: hsl(120, 100%, 50%);*    --> green (HSL)
######     *color: #RRGGBB;*    --> (HEX)
######  *}*

#### Adding 
##### Opacity to  RBA, HSL and HEX color schemes. We first convert it to RGBA, HSLA and add AA to HexaCode:
###### *pElement {*
######     *color: rgba(255, 0, 0, 0.6);*    --> red with opacity
######     *color: hsla(120, 100%, 50%, 0.3);*    --> green with opacity
######     *color: #00FF00);*    --> green with opacity
######  *}*

---

The first 3 values in each color scheme work the same in the individual color schemes the last value is for the ALPHA - a or A.
colorScheme(value1, value2, value3, a);
colorScheme --> #RRGGBBAA

Alpha RBG and HSL is a **_decimal_** number from zero to one. 
If alpha is zero, the color will be completely transparent. <br>
If alpha is one, the color will be opaque. 
The value for half-transparent would be 0.5.

Hex colors can have transparency by adding a 2 digit hexa value to end of 6 digit hexa value. Opacity of a hexadecimal color. Hex opacity ranges from 00 (transparent) to FF (opaque).

You can think of the alpha value as, “the amount of the background to mix with the foreground”.
When a color’s alpha is below one, any color behind it will be blended in.

One final thought in CSS color: rbga(0,0,0,0); is equivalent to color: transparent;






