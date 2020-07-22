# Starbucks Capstone

This project is intended to demonstrate all necessary and learned methods and concepts
in one final capstone project based on data provided by Starbucks. The data set contains 
customer profiles, a offer portfolio and a simulated set of interactions between 
customers and offers. These interactions mimic customer behavior on the Starbucks 
rewards mobile app.

The analysis is based on
* CRISP-DM (the six-phase cross-industry process for data mining),
* Data Visualization techniques and  
* Machine Learning algorithms.

Some ideas on how to take this project further are given in the section 
[Next Actions](#next_actions).


### Table of Contents

1. [Installation](#installation)
2. [File Descriptions](#files)
3. [Results](#results)
4. [Next Actions](#next_actions)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation and Dependencies<a name="installation"></a>
The project is running with Python 3. These libraries are required: 

* math
* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* json
* pickle

## File Descriptions <a name="files"></a> 
* `data/`<br/>
This folder containing the raw data (.json-files) used in the Jupyter Notebook. 

* `Exploration.ipynb`<br/>
This is the primary file containing all the source code and information on each
part of the analysis. 

* `*.pickle`<br/>
Pickle files used to skip the generation of the Data Frames Event Timeline and 
User-Income-Spending in the Juypter Notebook. 

## Results <a name="results">

You can find all the nity grity details of the analysis, including any part of
the code, in the Jupyter Notebook `Exploration.ipynb`. A condensed version can
be found as a blog post on https://fsteppich.github.io/blog/20200721-UD-DS-CapstoneStarbucks
    
## Next Actions <a name="next_actions">

The employed machine learning algorithms had a hard time finding a solid 
correlation between the user demographics, offer characteristics and the offer 
state / user engagement. Therefore I recommend the following next actions:

* Consider the findings of section *2. Data Understanding* of the Notebook when 
issuing new offers. This could further be refined into a automatic mechanism that...
* ... generates customer tailored offers (difficulty, type, ...) based on the 
curated timeline data.
* Apply other machine learning methods to better predict the offer state / user 
engagement. One such method might be to implement a recommendation engine that 
recommends offers from the portfolio according to user demographics and offer 
characteristics.
* Try to predict the revenue a users might generate based on user demographics 
and offer characteristics.

## Thanks, Authors, Acknowledgements<a name="licensing"></a> 
Any feedback that helps me to improve this project is welcome.  

You can find me on LinkedIn https://www.linkedin.com/in/fst/

This work is licensed under the GNU GPLv3 licence.

My thanks goes to [Udacity](https://www.udacity.com) for providing this insightful project
and to [Starbucks](https://www.starbucks.com/) for providing the data.

