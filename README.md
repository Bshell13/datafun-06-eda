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