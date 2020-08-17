# what-i-learned-week13
## CSS
### flexbox
- Design flexible responsive layout structure without using float or positioning.

- flex container as parent element, it becomes flexible by setting the display property to flex. The property is not inheritable.
``` 
.flex-container {
  display: flex;
} 
```

- flex-direction defines in which direction to stack the flex items
- flex-wrap property specifies whether the flex items should wrap or not.

### media queries

- @media,  a block of CSS properties only run if a certain condition is true.
- add break point by min-width and max-width

### grid
- a grid-based layout system, with rows and columns

#### Grid Lines
- The lines between columns are called column lines.

- The lines between rows are called row lines.

#### Grid Container
- grid container as parent element, by setting display property to grid 
- grid-template-columns property  defines the number of columns in the grid layout, and it can define the width of each column.
- grid-template-rows property defines the height of each row.

#### Grid Item
- grid-column property defines on which column(s) to place an item. Refer to line numbers, or use the keyword "span" to define how many columns the item will span.
- grid-row property defines on which row to place an item.

- grid-area property can be used as a shorthand property for the grid-row-start, grid-column-start, grid-row-end and the grid-column-end properties.

-  assign names to grid items:each row is defined by apostrophes ``` ' ' ```; the columns in each row is defined inside the apostrophes, separated by a space.
