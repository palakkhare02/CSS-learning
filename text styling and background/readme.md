🎨 CSS Fonts & Background Properties

This section explains how text styling and background styling work in CSS.

🔹 Font Family

The font-family property defines which font is used for text.

font-family: f1, f2, f3;


f1 → Primary font (first choice)

f2, f3 → Fallback fonts (used if the previous font is not available)

Always keep a fallback to avoid font issues

🔹 Font Size

The font-size property controls the size of the text.

📌 Absolute Unit
font-size: 16px;


px (pixels) → Fixed size

Does not change with screen size

📌 Relative Units
font-size: 1rem;
font-size: 1em;
font-size: 100%;


rem → Relative to root <html> font size

1rem = font size of html element

em / % → Relative to parent element

1em = 100% of parent font size

Best for components like buttons where container size matters

🔹 Viewport Units (Responsive Text)

Used for responsive designs.

font-size: 5vw;
font-size: 5vh;


vw (viewport width)

1vw = 1% of screen width

vh (viewport height)

1vh = 1% of screen height

Useful for responsive headings and layouts

🔹 Font Weight

Controls thickness (boldness) of text.

font-weight: 400;

Value	Meaning
100	Thin
300	Light
400	Normal
500–600	Medium / Semi-bold
700	Bold
800	Extra Bold
900	Black
🔹 Font Style

Defines the appearance of text.

font-style: italic;

normal

italic

oblique

🔹 Text Alignment

Aligns text horizontally.

text-align: center;

left

center

right

justify

🎯 Background Properties
🔹 Background Color

Sets background color of an element.

background-color: lightblue;

🔹 Background Image

Adds an image as background.

background-image: url("image.jpg");

🔹 Background Repeat

Controls image repetition.

background-repeat: no-repeat;

repeat

repeat-x

repeat-y

no-repeat

🔹 Background Position

Sets image position.

background-position: center;


Examples:

top left

center

bottom right

🔹 Background Size

Controls image size.

background-size: cover;


auto → Original size

cover → Covers entire container

contain → Fits inside container

Can also set manually: 100px 200px

🔹 Background Attachment

Controls scrolling behavior.

background-attachment: fixed;


scroll → Default (scrolls with page)

fixed → Background stays fixed.

✅ What I Learned

1-How to use fonts with fallback support

2-Difference between px, rem, em, vw

3-How to make responsive text

4- How to style backgrounds using images, size, and position