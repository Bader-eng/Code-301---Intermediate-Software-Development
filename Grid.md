## Grid Container:
1. display:Defines the element as a grid container and establishes a 
new grid formatting context for its contents.

2. grid-template-columns & grid-template-rows:Defines the columns and rows of the grid with a space-separated list of values. 
The values represent the track size, and the space between them represents the grid line.

3. grid-template-areas:Defines a grid template by referencing the names of the grid areas which are specified with
the grid-area property. Repeating the name of a grid area causes the content to span those cells. A period signifies 
an empty cell. The syntax itself provides a visualization of the structure of the grid.

4. justify-items: Aligns grid items along the inline (row) axis (as opposed to align-items which aligns along 
the block (column) axis). This value applies to all grid items inside the container.

5. align-items:Aligns grid items along the block (column) axis (as opposed to justify-items which aligns along the 
inline (row) axis). This value applies to all grid items inside the container.

## Grid Items:
1. grid-column-start & grid-column-end:Determines a grid item’s location within the grid by referring to specific grid lines. 
grid-column-start/grid-row-start is the line where the item begins, and grid-column-end/grid-row-end is the line where the item ends.

2. grid-area : Gives an item a name so that it can be referenced by a template created with the grid-template-areas property. Alternatively,
this property can be used as an even shorter shorthand for grid-row-start + grid-column-start + grid-row-end + grid-column-end.

3. justify-self: Aligns a grid item inside a cell along the inline (row) axis (as opposed to align-self which aligns along the block 
(column) axis). This value applies to a grid item inside a single cell.

