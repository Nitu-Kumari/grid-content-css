CSS Resets & Normalizers
~~~
The browser has its own stylesheet (called the user agent stylesheet) that it tries to apply before any of your stylesheets.
~~~
# Normalizers
~~~
 A normalizer maintains some default styling, but keeps it consistent between browsers. The most popular implementation of this is norm alizer.
 ~~~

 # Resets
 ~~~
 A CSS reset removes all default styling from a browser, maintaining only the distinctions between inline and block elements.

~~~
# CSS Positioning
~~~
position: static: This is the default for all elements.
 Normal document flow, will not accept top/right/bottom/left values.

position: relative: Creates a new positioning context for any absolutely positioned children, and itself.

position: absolute: Positions relative to the nearest relatively positioned parent, or the <body> if it doesn't have any.
 Absolutely positioned elements are removed from the document flow.

position: fixed: Positions relative to the viewport (display area of the browser window), and is not in the document flow.
~~~

# Grid Layout
~~~
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

grid is two-dimensional layout.
grid diving a page into major regions or defining the relationship in terms of size,position, and layer.

Display property:
An HTML element becomes a grid container by setting the display property to grid or inline-grid.
exmple
.grid-container {
  display: grid;
}
Question  What is RGBA?
RGBA stands for red green blue alpha. While it is sometimes described as a color space, it is actually the combination of an RGB color model .

Grid Columns
The vertical line of grid items are called columns.

Grid Columns
The vertical line of grid items are
called columns.

Grid Rows
The horizontal line of grid items are
called rows.

The grid-template-columns Property:

The grid-template-columns property defines the number of columns in your grid layout, and it can define the width of each column.

The value is a space-separated-list, value defines the length of the respective column.

If you want your grid layout to contain 4 columns, specify the width of the 4 columns, or "auto" if all columns should have the same width.

The grid-template-columns property can also be used to specify the size (width) of the columns.

The grid-template-rows property defines the height of each row.

The justify-content Property
The justify-content property is used to align the whole grid inside the container.


~~~~


















