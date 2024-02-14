# datafun-06-eda

## Virtual Environment
```shell
py -m venv .venv
.venv\Scripts\activate
```

## Install External Libraries
```shell
py -m pip install list of libraries
py -m pip freeze > requirements.txt
```
The list of libraries are the following:
-  jupyter
-  pandas
-  pyarrow
-  matplotlib
-  seaborn

## Create .gitignore
```shell
ni .gitignore
```
Make sure to include .venv/ and .vscode/ in the .gitignore file.

## Data Description
[Link to data](https://github.com/mwaskom/seaborn-data/blob/master/tips.csv)<br>
Column descriptions courtesy of [angela1c.com](https://www.angela1c.com/projects/tips-project-files/part1/#:~:text=According%20to%20the%20tips%20dataset,months%20working%20in%20one%20restaurant.)
-  **total_bill** *(float64)* - Total amount of the bill before tipping
-  **tip** *(float64)* - Amount of the tip for the bill
-  **sex** *(object)* - Sex of the bill payer
-  **smoker** *(object)* - Does atleast one person in the party smoke
-  **day** *(object)* - Day of the week, abbreviated
-  **time** *(object)* - Time of day based on the meal
-  **size** *(int64)* - Size of the party

After running a few basic statistics on the data set, here is what I have noticed:
1. The average party size is about 2.5 people with a standard deviation of 0.95.
2. 