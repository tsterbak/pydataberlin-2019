# Managing the end-to-end machine learning lifecycle with MLFlow

This Repository contains the resources for my tutorial **"Managing the end-to-end machine learning lifecycle with MLFlow"** at pyData/pyCon Berlin 2019.

# Basic setup

## Setup the environment
- clone this repository
- **with virtualenv (recommended)**
  - install virtualenv: `pip install virtualenv`
  - create a new environment: `virtualenv mlflow_tutorial`
  - activate the environment: `source mlflow_tutorial/bin/activate`
  - run `pip install -r requirements.txt`
  
- **with pipenv** 
  - install pipenv: `pip install pipenv`
  - run `pipenv install` in the directory of the Pipfile
  - activate the environment by `pipenv shell`

## The notebook
- Get the `hands_on_example.ipynb`
- run `jupyter notebook`

# Advanced setup

## Setup the environment
- install postgresql: `sudo apt-get install postgresql postgresql-contrib postgresql-server-dev-all`
