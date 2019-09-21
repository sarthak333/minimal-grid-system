# minimal-grid-system
Have you ever had to write your own responsve grid system for your project, even though you wanted to use a framework? But you also didn't have a use for dozens of custom components that came bundled with it? 
I've been facing the same issue and thus decided to make a very minimal and customizable responsive grid system for myself and other devs around the world.

Here's a simple working example of the grid http://sarthakjha.com/minimal-grid-system/

# Usable in your project?
   It's a pure CSS, 12-Columns based grid written in SASS. So if your project utilizes CSS then you can too enjoy the simplicity of this grid. Just import this file into your root stylesheet and use the classes globally throughout the project.
   
  For example => React.js, Angular.js, Vue.js, Rails, HTML/CSS/JS, and plethora others can use this grid.

# Usage
 
| CLASS  | USE |
| ------------- | ------------- |
| container  | This is the parent for our grid. Rows should be inside this tag  |
| row  | This is the class which will make your cells responsive. Should always be inside `container` and all the columns should be inside a row.  |
| row-static  | This is a variation of `row` that makes the grid unresponsive. i.e the grid will follow the set `column` width regardless of the viewport width. Should have columns   |
| col  | This is a dynamic `column`. If there's just 1 `col` in a row it'll take the space of the whole row. If there are 2 then each will take half the space, and so on.    |
| col-1  | Takes 1 space in the grid. |
| col-2  | Takes 2 space in the grid.  |
| col-3  | Takes 3 space in the grid.  |
| col-4  | Takes 4 space in the grid.  |
| col-5  | Takes 5 space in the grid.  |
| col-6  | Takes 6 space in the grid.  |
| col-7  | Takes 7 space in the grid.  |
| col-8  | Takes 8 space in the grid.  |
| col-9  | Takes 9 space in the grid.  |
| col-10  | Takes 10 space in the grid.  |
| col-11  | Takes 11 space in the grid.  |
| col-12  | Takes 12 space in the grid.  |



There are also a few commonly and extensively used classes that have been added here just for a good measure.

| CLASS  | USE |
| ------------- | ------------- |
| center  | Will perfectly center the child elements both vertically and horizontally. |
| center-v  | Will center align the child elements vertically |
| center-h  | Will center align the child elements horizontally |
| full-size  | takes up the full size of the parent container. |
| full-screen  | takes up the size of the whole screen |

# Points to note
 * This is a 12-columns based grid, thus the suffix of the columns used in any row should always add upto 12.
 * All the column classes can be both responsive or non-responsive, depending on the row class chosen.
 * This is a skeleton grid. It might not work exactly as you would like it to, thus feel free to make and suggest chagnes. Also, I'd love it if you were to make a separate branch for your version of this grid and share it with others too.
 
 # Happy Coding!

