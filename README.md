# Module 12 challenge
# nosql-challenge


## About:
This project is part of the Module 12 Challenge focused on NoSQL databases, specifically utilizing MongoDB. The aim of this challenge is to deepen understanding of NoSQL concepts and to gain hands-on experience with MongoDB operations, including creating databases, performing CRUD (Create, Read, Update, Delete) operations, and implementing aggregation pipelines, utilyzing a JSON file of establishments, to sort, filter, add and manipulate the documents to only see what is asked. 

### Dependencies to import:
    1. from pymongo import MongoClient
    2. import pandas as pd
    3. from pprint import pprint
    4. from decimal import Decimal
    5. import re


#### How to run:
    1. Install dependancies
    2. CD into nosql-challenge/Starter_Code
    3. Open a git Bash terminal here and run the following. ("mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json")
    4. Run all cells in the NoSQL_setup_starter.ipynb
    5. Run all cells in the NoSQL_analysis_starter.ipynb


#### Sources:
    1. Class time / office hours / Teacher Aides
    2. Tutors: Carlos Gattorno / Lucas
    3. Xpert Learning
    4. CS50P Week 7 class on regex. https://cs50.harvard.edu/python/2022/weeks/7/
    5. https://docs.python.org/3/library/decimal.html
    6. Stack Overflow
    7. https://pandas.pydata.org/
    8. Chat GPT