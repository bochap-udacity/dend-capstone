# Project: Data Engineering Capstone Project

## Overview
The purpose of the data engineering capstone project is to give you a chance to combine what you've learned throughout the program. This project will be an important part of your portfolio that will help you achieve your data engineering-related career goals.

In this project, you can choose to complete the project provided for you, or define the scope and data for a project of your own design. Either way, you'll be expected to go through the same steps outlined below.

### Udacity Provided Project
In the Udacity provided project, you'll work with four datasets to complete the project. The main dataset will include data on immigration to the United States, and supplementary datasets will include data on airport codes, U.S. city demographics, and temperature data. You're also welcome to enrich the project with additional data if you'd like to set your project apart. 

## Running this code

### Prerequisites

1. Python 3.6 and above
2. GIT setup and configured for SSH
3. Docker (If running locally)

### Running locally
1. Clone repository by running `git clone git@github.com:seetdev/dend-capstone.git`
2. Go into the cloned folder
3. Create folders for `model_data`, `raw_sas_data`, `sas_data` and `staging_data`
4. Setup the docker image by running `docker build --tag udacity-dend/pyspark-notebook .`
5. Start docker container by runnin `docker run --rm -d -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v $PWD:/home/jovyan/work --name spark udacity-dend/pyspark-notebook`