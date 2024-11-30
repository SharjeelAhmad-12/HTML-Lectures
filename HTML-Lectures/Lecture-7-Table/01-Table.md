### HTML Table Element (<table>)

The <table> element is used to represent tabular data in HTML. It allows the presentation of information in rows and columns, which is ideal for displaying data like schedules, financial data, or other structured content.

## 1. What is an HTML Table?
An HTML table is a collection of rows and columns used to display tabular data. Tables are created using the <table> tag, with rows defined by <tr>, headers by <th>, and data cells by <td>.

Table Structure
A table consists of several parts:

<table>: The container element that holds all the other table elements.
<tr> (Table Row): Represents a row in the table.
<th> (Table Header Cell): Represents a header cell, typically used to define the column labels.
<td> (Table Data Cell): Represents a data cell where the actual content of the table is placed.
<caption>: Defines the title of the table (optional).
<thead>, <tbody>: Optional grouping elements that organize rows into header, body.

Syntax: 

<table>
  <caption>Table Title</caption>
  <thead>
    <tr>
      <th>Heading 1</th>
      <th>Heading 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
    </tr>
    <tr>
      <td>Data 3</td>
      <td>Data 4</td>
    </tr>
  </tbody>
</table>


## Explanation of Tags
<table>: Wraps the entire table.
<caption>: Provides a title for the table, which is placed above the table.
<thead>: Groups the header row(s) and is typically used for column headers.
<tbody>: Groups the main body content of the table.
<tr>: Defines a row in the table.
<th>: Defines a header cell. By default, text inside a <th> is bold and centered.
<td>: Defines a data cell. These cells hold the main content of the table.

## Table Attributes
**border**: Specifies the width of the table border (e.g., border="1").
**cellspacing**: Defines the space between the cells.
**cellpadding**: Defines the space inside each cell.
**Example**
  <table border="1" cellpadding="10" cellspacing="0"> Add border ,cellpadding,cellspacing to the table.

**rowspan**: This attribute allows a cell to span multiple rows. It is used to merge cells vertically.
**Example**: <td rowspan="2"> spans the cell across two rows.

**colspan**: This attribute allows a cell to span multiple columns. It is used to merge cells horizontally.
**Example**: <td colspan="2"> spans the cell across two columns.

- Both attributes are used within <td> or <th> elements to create complex table layouts.