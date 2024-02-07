# CSS Cheat Sheet

## Table of Contents

- [CSS Cheat Sheet](#css-cheat-sheet)
  - [Table of Contents](#table-of-contents)
  - [Selectors](#selectors)
  - [Box Model](#box-model)
  - [Flexbox](#flexbox)
  - [Grid](#grid)
  - [Properties](#properties)
  - [Pseudo-Classes](#pseudo-classes)
  - [Pseudo-Elements](#pseudo-elements)
  - [Functions](#functions)
  - [At-Rules](#at-rules)

## Selectors

- `*` { Universal selector }
- `.classname` { Class selector }
- `#id` { ID selector }
- `element` { Type selector }
- `element, element` { Grouping selector }
- `element element` { Descendant selector }
- `element > element` { Child selector }
- `element + element` { Adjacent sibling selector }
- `element ~ element` { General sibling selector }
- `[attribute]` { Attribute selector }

## Box Model

- `margin` { Controls the outer space around an element }
- `border` { The boundary between margin and padding }
- `padding` { Controls the space between border and content }
- `width/height` { Set the width/height of the content area }

## Flexbox

- `display: flex;` { Enables flex context for its children }
- `flex-direction` { Defines the direction of flex items }
- `justify-content` { Aligns flex items along the main axis }
- `align-items` { Aligns flex items along the cross axis }
- `flex-grow` { Defines the ability for a flex item to grow }
- `flex-shrink` { Defines the ability for a flex item to shrink }
- `flex-basis` { Defines the default size of an element before remaining space is distributed }

## Grid

- `display: grid;` { Enables grid layout }
- `grid-template-columns / grid-template-rows` { Define the columns/rows of the grid }
- `grid-column-start / grid-column-end` { Define where a grid item starts/ends in the grid columns }
- `grid-row-start / grid-row-end` { Define where a grid item starts/ends in the grid rows }
- `grid-area` { Shorthand for grid-row-start / grid-column-start / grid-row-end / grid-column-end }
- `justify-items` / `align-items` { Aligns grid items inside their cells }

## Properties

- `color` { Text color }
- `background` { Background properties }
- `font-family` { Typeface }
- `font-size` { Size of the font }
- `text-align` { Horizontal text alignment }
- `position` { Element positioning method }
- `top / right / bottom / left` { Positioning offsets }
- `overflow` { What happens if content overflows an element's box }

## Pseudo-Classes

- `:hover` { Applies when mouse over }
- `:focus` { Applies when element has focus }
- `:active` { Applies when element is activated }
- `:nth-child(n)` { Targets the nth child element }

## Pseudo-Elements

- `::before` { Insert content before an element's content }
- `::after` { Insert content after an element's content }
- `::first-letter` { Targets the first letter of an element }
- `::first-line` { Targets the first line of text in an element }

## Functions

- `calc()` { Perform calculations to determine CSS property values }
- `var()` { Use CSS custom properties (variables) }
- `attr()` { Retrieve the value of an HTML attribute }

## At-Rules

- `@import` { Include external CSS file }
- `@media` { Apply part of CSS only if a certain condition is true }
- `@keyframes` { Describe animation sequences }
- `@font-face` { Include external fonts }
