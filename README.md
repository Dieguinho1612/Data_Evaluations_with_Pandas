# Evaluating Data with Pandas

This repository contains evaluations of provided data, conducted using the Python 3 package Pandas. The corresponding code was uploaded to this repository with the permission of the respective client for whom it was created. It should be noted that dummy data was used for illustration purposes. 

## BASF: Deciding between contract options with Deutsche Bahn

Here, the task was to decide between different options of contracts that the client BASF could do with the German train company Deutsche Bahn. The client had a [text-document](https://github.com/Dieguinho1612/Data_Evaluations_with_Pandas/blob/main/BASF_optimizing_contract_with_Deutsche_Bahn/DB_Daten_Can.txt) containing the data about the 20 most frequent travel routes of its employees in the past year and the prices for each of these travel routes for every possible type of contract.<br>

I performed an in-depth analysis on this data to give a mathematical recommendation of which contract to use. For this, I created a [Notebook](https://github.com/Dieguinho1612/Data_Evaluations_with_Pandas/blob/main/BASF_optimizing_contract_with_Deutsche_Bahn/DeutscheBahnContract.ipynb) with Jupyter. It has a simple instruction immanent. Therefore, the client can reuse it to his liking, should he want to reassess different contract options in the future or should the usage of the travel routes change. He only has to state the file name of the data set that should be evaluated. The Notebook then completes the rest of the task automatically within seconds.<br>

An [assessment of my work](https://github.com/Dieguinho1612/Data_Evaluations_with_Pandas/blob/main/BASF_optimizing_contract_with_Deutsche_Bahn/Reference_Mr.%20Diego%20Hitzges%20(Can).pdf) by BASF is appended.

## Ezlo Innovation: Evaluating Employees Performance

A manager in the IT-company was receiving performance data of all employees of the respective team every day. Every employee would create an excel-sheet, listing performed activities during the day together with the corresponding starting and end times. In the end of every month, the manager had the task to evaluate all given sheets, filter out activities that were not job related and calculate the efficiency of each employee, being the time that was spend on productive activities divided by the entire working time. The most efficient employee would then get a bonus. Furthermore, the average efficiency of the entire team should get calculated. Doing this task took the manager 1 to 2 entire working days each month.<br>

I created a  [Notebook](https://github.com/Dieguinho1612/Data_Evaluations_with_Pandas/blob/main/Performance_Evaluation_of_Employees/Performance_Evaluation.ipynb) with google colaboratory to automate this task. It has a simple instruction of use immanent. The data has to be stored in the correct repository, defined by the month and year. The Notebook then asks the user which month and year should be evaluated. Afterwards, it automatically completes the above procedure. As a consequence, the manager could complete this task in less than 5 minutes every month. The results were compared with the ones she created manually, which lead to the observation that the Notebook did less mistakes filtering out activities that were not job related, resulting in even more accurate performance measurements.
