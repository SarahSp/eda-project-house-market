# King County House Price Dataset

I completed this EDA as part of the 6-month part-time Data Practitioner bootcamp at [neuefische](https://www.neuefische.de/en) during 5 days (2.5 full work days). It is my first EDA project. 

The assignment was to explore a dataset of home sales using data analysis techniques to derive recommendations for a fictional client. 
More information on the assignment can be found in [assignment.md](https://github.com/SarahSp/eda-project-house-market/blob/project_assignment/assignment.md). 

[EDA_project.ipynb](https://github.com/SarahSp/eda-project-house-market/blob/main/EDA_project.ipynb) is a Jupyter Notebook that describes the steps taken during this EDA, the hypotheses and conclusions. [column_names.md](https://github.com/SarahSp/eda-project-house-market/blob/main/column_names.md) includes descriptions of the data set columns. 

[EDA Project - King County House Market.pdf](https://github.com/SarahSp/eda-project-house-market/blob/main/EDA%20Project%20-%20King%20County%20House%20Market.pdf) includes a slide-show with the final results and insights for the client. 

## Requirements

- pyenv
- python==3.11.3

## Setup

One of the first steps when starting any data science project is to create a virtual environment. For this project you have to create this environment from scratch yourself. However, you should be already familiar with the commands you will need to do so. The general workflow consists of... 

* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

In order to install the environment you can use the following commands:

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
