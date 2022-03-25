HTML TABLES
Styling with CSS
Tables, by default, are very bland. They have no borders, the font color is black, and the typeface is the same type used for other HTML elements.

CSS, or Cascading Style Sheets, is a language that web developers use to style the HTML content on a web page. You can use CSS to style tables. Specifically, you can style the various aspects mentioned above.

table, th, td {
  border: 1px solid black;
  font-family: Arial, sans-serif;
  text-align: center;
}
The code in the example above demonstrates just some of the various table aspects you can style using CSS properties.

Instructions
1.
We’ve included a .css file containing instructions for styling the HTML content in the index.html file.

In style.css, set the font-size of all table headings (th) and table data (td) to 18 pixels (18px).

Checkpoint 2 Passed

Hint
The th, td selector already exists for you in style.css.

Navigate to the section of the CSS that looks like this:

th, td {
  font-family: 'Lato', sans-serif;
  font-weight: 400;
  padding: 20px;
  text-align: left;
  width: 33.3333%;
}
Add the following line somewhere between those two curly brackets ({}):

 font-size: 18px;