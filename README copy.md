# ds-project-template

This is a EDS project for Data Science.

## Requirements

- pyenv
- python==3.11.3

## Setup


* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`


Please, check before that you met the requirements

```bash
pip freeze > requirements.txt
```

Intallin the enviroment
```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### In this repository

You will find the requirement document where you will informed of the packages and version that you will need.

Besides is to find a notebook with the task explained point by point, and a second notebook with the description of the columns of the dataset.

### Task

The task you will find it in the main notebbok. This project is made in order to lern and get better in the topic of Exploratory Data Analisys. The Dataset goes by the na me of King County Data Set.
You will find two dataset and both have to be merged in one table. 
Through this notebook I will go back and forth cleaning the data, trying to understanding it and get the best solution for my client.

I hope you will have jun with it!
p