 # Burgos_Jazlibeth_Lab8
All about working with SASS.

Update: My explanation on how my SASS project functions this way;

Initially, I began by making the lines 38-46 a paragraph to edit the element. Then I gave it it's own class called "mychanges". Next I went and added some new variables, making some adjustments to the text's font family, font size, a border color, width, and style as well as a background color. Then I went a created a mixin to include these variables and called the mixin "mylabchanges" to avoid confusion. Finally, the last piece to the puzzle is to actually connect these variables and mixins to the style sheet, so I referenced the paragraph by its class, and told it to include the mixin which I called by its name. This is how my SASS lab functions.