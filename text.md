### defferent-beetween flext and grid

Grid and flexbox
The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time. The two specifications share some common features, however, and if you have already learned how to use flexbox, the similarities should help you get to grips with Grid.

## One-dimensional versus two-dimensional layout

A simple example can demonstrate the difference between one- and two-dimensional layouts.

In this first example, I am using flexbox to lay out a set of boxes. I have five child items in my container, and I have given the flex properties values so that they can grow and shrink from a flex-basis of 150 pixels.

I have also set the flex-wrap property to wrap, so that if the space in the container becomes too narrow to maintain the flex basis, items will wrap onto a new row.

<div class="wrapper">
  <div>One</div>
  <div>Two</div>
  <div>Three</div>
  <div>Four</div>
  <div>Five</div>
</div>
Copy to Clipboard
.wrapper {
  width: 500px;
  display: flex;
  flex-wrap: wrap;
}
.wrapper > div {
  flex: 1 1 150px;
}

[mdn link](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout#:~:text=already%20be%20using.-,Grid%20and%20flexbox,columns%20at%20the%20same%20time.)
