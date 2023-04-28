# Evaluating Data with Pandas

In this repository there are some evluations of given data with the package Pandas from Python 3.

## BASF: Deciding between contract options with Deutsche Bahn

Here, the task was to decide between different options of contracts that the client BASF could do with the German train company Deutsche Bahn. The client had several information about the 20 most frequent travel routes of its employees in the past year and the prices for each of these travel routes for every possible type of contract.<br>

I performed an in-depth analysis on this data to give a mathematical recommendation of which contract to use. An assessment of my work by BASF is appended.

## Evaluating Employees Performance

A manager in an IT-company was receiving performance data of all employees of the respective team every day. Every employee would create an excel-sheet, listing performed activities during the day together with the corresponding starting and end times. In the end of every month, the manager had the task to evaluate all given sheets, filter out activities that were not job related and calculate the efficiency of each employee, being the time that was spend on productive activities divided by the entire working time. The most efficient employee would then get a bonus. Doing this task took the manager 1 to 2 entire working days each month.<br>

I created a google colaboratory notebook to automatize this task. The data has to be stored in the correct repository, defined by the month. The notebook then asks the user which month should be evaluated. Afterwards, it automatically completes the above procedure. As a consequence, the manager could complete this task in less than 5 minutes every month. The results were compared with the ones created manually, which lead to the observation that the notebook did less mistakes filtering out activities that were not job related, resulting in even more accurate performance measurements.
