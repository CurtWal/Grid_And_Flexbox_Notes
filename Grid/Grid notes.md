What is CSS Grid?

- CSS Grid is a powerful tool that CSS gives us to easily align items and create two-dimensional layouts

Grid Containers & Grid Items

- The grid container is the element that holds grid items.
- Grid items are direct children of grid containers.
- A container is created with the displacy: grid;

ex:
<div class='grid-container'>
    <div>Grid Item1</div>
    <div>Grid Item2</div>
    <img src="pic.png" alt="also a grid item">
    </div>

Grid Container Properties :
- grid-template columns
- grid-template-rows
- grid-gap
- grid-auto-rows
- grid-auto-columns
- grid-template-areas
- justify-content
- align-items

Grid Items Properties:
- grid-column
- grid-row
- grid-area
- align-self
- justify-self

Two Dimensional Layouts

- Unlike Flexbox, which is one-dimensional and can be either a row or column, a CSS Grid allows us to create two-dimensional layouts with rows AND cloumns