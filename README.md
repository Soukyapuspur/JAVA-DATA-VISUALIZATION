We basically had 2 major tasks. One involves creating the GUI, and the other is retrieval of information from the table and pass it to the jfreechart object to generate a pie chart. Let us look at the GUI first:

1. The input screen consists of 2 textfields, a Jtable , a Jpanel for pie chart.

2. Our user interface consists of 3 buttons “Add Data”, “Pie Chart” & “Reset” respectively.

Moving to generating pie chart, we will apply the following:

1. We firstly create an object of DefaultPieDataset class.

2. Then we enter the entity name & its value using setValue method using the object you made.

3. Use method createPieChart of ChartFactory class and pass your object.

4. Finally, add the piechart to the Jpanel.

