# HTML-CSS-Assignment

## Semantic tags add meaning to your Html, They tell both developer and browser what kind of content is being presented.

## Meta tag are snippets of text present in head section of html document that provides information about data of website.They are used for SEO, page description and controlling the behaviour of web page.

## example of semantic tag - header, nav, footer, article, main, section, figure, figurecaption

## example of meta - 

## flex -

### flex is a CSS layout model used to efficient way to distribute space and align items within a container. it is commonly used for responsive layout without more relay on float.

### difference between display:flex and flex:1 1 200px

The display: flex property is used to define a flex container. When you apply display: flex to a container element, all of its direct children (referred to as flex items) are laid out according to the Flexbox model.

The flex property is applied to individual flex items inside a flex container. It is a shorthand property for flex-grow, flex-shrink, and flex-basis, which control how a flex item should grow, shrink, and what its base size should be within the flex container.

flex-grow: 1; allows the item to grow to fill available space.
flex-shrink: 1; allows the item to shrink if there’s not enough space.
flex-basis: 200px; sets the initial size of the item to 200px before growing or shrinking.

## grid -

## why meta tag are not closing tag - self closing tag or void

## Position:---------------------

### static- the element is positioned according to normal flow of document. No top, left, right and bottom will applied.

### relative - the element is positioned according to relative to normal flow of document. right, left can be applied.

### absolute - the element is positioned according to relative to nearest positioned ancestor. top, left, right

### fixed - the element is positioned according to relative to viewport,even when the page is scrolled, its postion dont change.


## diff bt flex and grid?

Flexbox and Grid are two popular layout systems in CSS that help you manage and arrange content on the web. While they share some similarities, they have distinct differences in their approach, usage, and application.

Flexbox
A one-dimensional layout system that helps you manage layout, alignment, and distribution of elements in a container.
Best suited for:
Linear layouts (e.g., navigation bars, button groups)
Single-row or single-column layouts
Layouts with variable content width or height
Key properties:
flex-direction (row, column, row-reverse, column-reverse)
justify-content (flex-start, center, space-between, space-around)
align-items (flex-start, center, baseline, stretch)
Grid
A two-dimensional layout system that enables you to create complex, grid-based layouts.
Best suited for:
Multi-row and multi-column layouts
Layouts with fixed or variable grid cell sizes
Complex, structured content (e.g., tables, dashboards)
Key properties:
grid-template-columns and grid-template-rows (define grid structure)
grid-column and grid-row (place items in the grid)
justify-items and align-items (align items within grid cells)
Key differences
Dimensionality: Flexbox is one-dimensional, while Grid is two-dimensional.
Layout structure: Flexbox is ideal for linear layouts, while Grid is better suited for complex, grid-based layouts.
Item placement: Flexbox relies on justify-content and align-items for item placement, whereas Grid uses grid-column and grid-row for precise placement.
When to use each:

Use Flexbox for simple, linear layouts or when you need to manage variable content width or height.
Use Grid for complex, structured content or when you need to create a multi-row and multi-column layout.
Do you want me to elaborate on any specific aspect of Flexbox or Grid?

### display: block, inline-block, none, visible, inline

### difference between span and div