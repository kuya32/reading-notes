# Read: 05 - Design web pages with CSS

## CSS rule contains two parts

### Selector

- indicates which element the rules applies to
- Pg. 238 shows selector types

### Declaration

- Indicates how the element referred to in the selector should he styled

### Declaration sits inside the curly brackets and holds:

- Property
    - Indicates the aspects of the element you want to change
- Values
    - Specify the settings you want to use for the chosen properties

## Advantages of keeping CSS rules separate

- All of your web pages can share the same style sheet
- Once CSS stylesheet is downloaded, the rest of the site will load faster
- The one CSS style sheet, rather than changing the CSS rules on every pages
- CSS rules usually appear in a separate document, although they may appear within an HTML

## Three ways to specify color in CSS:

- RGB
- Hex code
- Color names

## Color code examples

/*color name */
h1 {
Color: DarkCyan;}
/*hex code*/
h2 {
Color: #ee3e80;}
/* rgb value */
p {
Color: rgb(100, 100, 100);}

## Background color code examples

body {
	Background-color: rgb(200, 200, 200);}
h1 {
	Background-color: DarekCyan;}
h2 {
	Background-color: #ee3e80;)
p {
	Background-color: white;}

## A lot of factors plays into choosing a color to style your website

- Creates the mood and evokes reaction

## Contrast plays a huge role between text and background

- Helps user to read website better
- Less stress on your eyes

## CSS3 brings

- Opacity (rgba)
    - Specify the opacity of an element and any of its child elements
- New specifications
    - Hue
        - The colloquial idea of color
    - Saturation
        - The amount of gray in a color
    - Lightness values
        - The amount of white (lightness) or black (darkness) in a color
- HSL & HSLA
    - Hsl - an alternative way to specify color
    - Hsla - specify color properties like before but adds a value which represents transparency

[Back to Main](README.md)