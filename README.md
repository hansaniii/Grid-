# CSS Grid and Fractional Units (fr)
CSS Grid is a powerful layout system in CSS that allows you to create complex, responsive grid-based layouts on the web. Grid divides the webpage into rows and columns, making it easier to control where elements are placed and how they resize.

**Grid Basics:** 
The Grid layout system is created using display: grid;. You can define rows and columns using **grid-template-rows** and **grid-template-columns** , and then place elements into these grids.

**Fraction (fr) Units:**
The fr unit in CSS Grid represents a fraction of the available space in the grid container. It divides the container into equal portions based on the number of **fr** units assigned.

**Example:
css**
.container {
  display: grid;
  grid-template-columns: 1fr 2fr; /* 1 part for the first column, 2 parts for the second */
}

In this example, the container is divided into 3 parts. The first column gets 1 part, and the second column gets 2 parts of the available space.

**CSS Flexbox**
CSS Flexbox (Flexible Box Layout) is another layout system that is simpler and more focused on distributing space between items in a container and aligning them.

**Flexbox Basics:**
To use Flexbox, you set the container to display: flex;. This makes all child elements (flex items) align in a row (horizontally by default) or column (if you set flex-direction: column;).

**Key Properties:**
justify-content: Aligns flex items along the main axis (e.g., left, right, center).

**align-items:** 
Aligns items along the cross axis (e.g., vertically in a row layout).

**flex-grow:**
Controls how much a flex item should grow relative to others.

**Example:
css**
.container {
  display: flex;
  justify-content: space-between; /* Distribute space between items */
}

**Differences**
Grid is great for two-dimensional layouts (rows and columns), while Flexbox is more focused on one-dimensional layouts (either a row or column).
Grid allows for more complex layouts like overlapping elements, while Flexbox excels at distributing items within a container (flexible alignment).
**Fractional Units (fr)** are specific to Grid, while Flexbox uses flexible sizing with properties like flex-grow and flex-shrink.
