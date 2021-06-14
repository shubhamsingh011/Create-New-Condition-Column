# Create-New-Condition-Column


To open a query, locate one previously loaded from the Power Query Editor, select a cell in the data, and then select Query > Edit. For more information see Create, load, or edit a query in Excel.

Select Add Column > Conditional Column. The Add Conditional Column dialog box appears to help you create a syntactically correct formula:

if condition then expression else expression

In the New column name box, enter a unique name for your new conditional column. In the example, we change the name from Custom to Region.

In the Column name list box, select a column name. In the  example, we select Name & Postal, which is a list of American states.

In the Operator list box, select an operator. In the example, we select Contains.

In the Value box, enter the appropriate value. In the example, we enter "Washington".

In the Output box, enter the output value that your conditional column should display when the if condition is true. In the example, we enter "West".

If you want to add an else expression when the condition is false, select Add Clause, and then repeat steps 4 to 6. In the example, additional regions are added including South, Northeast, and Midwest. This is commonly referred to as a nested condition.

To delete or rearrange clauses, select More (...)  next to the clause, and select a command.  

Optionally, add a final else expression. You can enter a value, another column, or a parameter.

Select OK.

Notes   

By default, a conditional column doesn’t have a data type automatically defined. For more information, see Add or change data types.

To modify the condition, select the Edit Settings  Settings icon  icon next to the Added Conditional column step in the Applied Steps of the Query Settings pane.
