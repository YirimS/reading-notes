# Object-Oriented Programming, HTML Tables.

When presenting information in a table, you need to thinks in terms of a grid made up of rows and columns (like a spreadsheet).

## What is a table?

A table represents binformation in a grid format. Examplkes of tables include finacial reports, TV schedules, and sports results.

Basic table structure:

- < table >
the table element is used to create a table. The contents of the table are written out row by row.

< tr > 
You indicate the start of each row using the opening < tr > tag (the tr stands for table row.)  It is folowed by one or more < td > elements(one for each cell in a row.)

< td >
Each cell of a table is reprewsented using the < td > element (the td stands for table data.)

< th >
This element is used just like the < td > but it's purpose is to represent the heading for either a columbn or row (the th stands for table head.)
For long tables you can split the table into a < head >, < tbody >, and < tfoot >.

You can make cells of a table span more than one row of columns using the rowspan and colspan attributes.

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>

# Creating an object

An  object is a series of variables and functions that represent the world around you.

Functions allow you to group a set of related statements together to represent a single task. Functions can take parameters (information required to do their job) and may return a value.

 var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
