# Starbucks-Offers-Analysis

## Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#project-motivation)
3. [File Description](#file-description)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing-authors-and-acknowledgements)

## Installation
### Dependencies
* Python >=3.7
* matplotlib >= 3.4.2
* numpy >= 1.21.1
* pandas >= 1.3.1
* seaborn >= 0.11.1

### User Installation
Assuming you already have Python>3.7 up and running, the easiest way to install 
the requirements is using **pip** or **conda**. This tutorial assumes using _pip_
for the installation purposes.

Create a virtual environment to set up the project. (Optional Step)

``
python3 -m venv <my_env>
``

cd to the root directory of the code and install the requirements using

``
pip install -r requirements.txt
``

## Project Motivation
For this project, I was interested in Starbucks app data. The questions of 
interest that we will be exploring are:
1. What are the Income Distribution Groups in the data?
2. In what year,  the people under observation joined the app?
3. What kind of offers are sent to each demographic group?
4. How are the people likely to respond to each offer?
5. Is there a group who completes the offer without viewing it?
6. Who is most likely to complete an offer?
7. What is the money spending trend among all groups under consideration?

## File Description
For the purpose of answering above questions, this project contains a single notebook
that addresses the questions. The data under consideration is available as 
three json files in the data folder.

## Results
The findings of the analysis are discussed in the jupyter notebook as well as in
a blog post [here](https://medium.com/@RamshahJahangir/analyzing-target-audience-for-starbucks-app-offers-59dedb7e6490).

## Licensing, Authors, and Acknowledgements
A special thanks to Starbucks for making this data available to explore, and to
Udacity for all the resources and help in completing this project.
