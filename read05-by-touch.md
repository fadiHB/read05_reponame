
# css
CSS treats each HTML e XX lement as if it appears inside
its own box and uses rules to indicate how that
element should look.

XX Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).

XX Different types of selectors allow you to target your
rules at different elements.

XX Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.

XX CSS rules usually appear in a separate document,
although they may appear within an HTML page.

## Foreground Color
### color
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
1-rgb values 
2-hex codes
3-color names

### background-color
CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of 
background color in the same
three ways you can specify
foreground colors

#### Contrast
When picking foreground and background
colors, it is important to ensure that there is
enough contrast for the text to be legible

### CSS3 HSL & HSLA
The hsl color property has
been introduced in CSS3 as an
alternative way to specify colors.
The value of the property starts
with the letters hsl, followed
by individual values inside parentheses for:

hue
This is expressed as an angle
(between 0 and 360 degrees).

saturation
This is expressed as a
percentage.

for examle:
p {
background-color: #ffffff;
background-color: hsla(0,100%,100%,0.5);}

### Summary 
X XColor not only brings your s XX ite to life, but also helps
convey the mood and evokes reactions.

XX There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.

XX Color pickers can help you find the color you want.

XX It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).

XX CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.

XX CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.

