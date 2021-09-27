The details of the solution and implementation for the min spreadsheet are listed below:

1. Analyzed the requirements and searched the relevant information online.
   I have been fortunate to find a source code that meets parts of the third step.
   I planed to store data by dynamically create tables, tr, td using input
   to store data.

2. Created a project min-spreadsheet using VS Code to create the HTML, JS file,
   and CSS files. Using the Live Server to view the effect page.

3. Used 2 for loops to create the table, tr, td, store data with input,
   and generated the input id according to the line number and column when
   generated, which is convenient for future operation. Generated the
   column label for each column based on ASCII. Specific numbers of rows
   and columns can be reset to meet the needs of changes. Also added
   a refresh button, called the reload page method to implement the page refresh.

4. Implemented calculation of the sum of these two cells and displayed
   the result using the input on click event. After completing, I added
   two cells subtraction functions. In the future, new features such as
   multiplication, can be used in the same way with the subtraction function.

5. Implemented calculation of the sum of all cells in the range and
   displayed the result with the same method as the above (number 4).
   Used the for loop to calculate all cells' values.
   The current summation only supports the cells that are in the same column,
   for example, =sum (A3: a1). If I have more time, I will achieve different
   more, such as =sum (A1: B3).

6. Using the table and input styles to implement support for
   formatting for all data for the table and data in the table.

7. Testing and modifying the bugs and uploaded the code to Github.

8. Next, if I have more time to improve the quality of this project,
   I will consider optimization of performance and consider adding
   more functions.
