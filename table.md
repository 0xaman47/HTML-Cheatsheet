### Table :
>  A HTML table is used to arrange data in tabular form into rows and columns.
```
<caption> : Title of table.
<table> : represents data in a two-dimensional table comprised of rows and columns.
<thead> : header content of table.
<tbody> : primary content of table.
<th> : Heading under table data.
<td> : contain main data in the table.
<tr> : row in HTML table.
<tfoot> : defines a set of rows summarizing the columns of the table as per requirement.
```
```
Ex : 
<!DOCTYPE html>
<html>
<head>
   <title>0xaman47</title>
</head>
<body>
   <!-- table starts here -->
   <table>
      <!-- Table Caption -->
      <caption>HTML Learning</caption>
      <!-- Table row starts -->
      <tr>
         <!--Headers -->
         <th>Programming Languages</th>
         <th>Development</th>
         <th>Placement and Test series</th>
      </tr>
      <!-- Table row ends -->
      <tr>
         <!-- Table data -->
         <td>C programming </td>
         <td>Full stack development</td>
         <td>Google SDE preparation </td>
      </tr>
      <tr>
         <td>Java programming</td>
         <td>Backend development</td>
         <td>Flipkart SDE preparation</td>
      </tr>
      <tr>
         <td>Angular </td>
         <td>Frontend Development</td>
         <td>Amazon SDE preparation</td>
      </tr>
      <!-- Table Footer starts here -->
      <tfoot>
         <tr>
            <td>Footer content</td>
         </tr>
      </tfoot>
      <!-- Table footer ends here -->
   </table>
</body>
</html>
```