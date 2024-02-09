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
[Link to data](https://github.com/mwaskom/seaborn-data/blob/master/tips.csv)
Column descriptions courtesy of [angela1c.com](https://www.angela1c.com/projects/tips-project-files/part1/#:~:text=According%20to%20the%20tips%20dataset,months%20working%20in%20one%20restaurant.)
-  **total_bill** *int* - Total amount of the bill before tipping
-  **tip** *int* - Amount of the tip for the bill
-  **sex** *str* - Sex of the bill payer
-  **smoker** *str* - Does atleast one person in the party smoke
-  **day** *str* - Day of the week, abbreviated
-  **time** *str* - Time of day based on the meal
-  **size** *int* - Size of the party