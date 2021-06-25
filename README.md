# Starbucks Offers Challenge

### Table of Contents

1. [Installation](#installation)
2. [Instruction](#instruction)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

All the libraries required for running the app are listed in the requirement.txt file.
For installing these libraries, only run this command with Python 3 in root path:

```
$ pip install -r requirements.txt
```


## Instruction <a name="instruction"></a>

Execute all cells of starbucks_offers.ipynb


## Project Motivation<a name="motivation"></a>

This is the final project for the Udacity Data Science Nanodegree program. For this project I am interestested in building a machine learning model to predict offer success. 
I develop all those steps: 
I: Business Understanding
II: Dependencies
III: Data Understanding
IV: Data Wrangling
1. Missing data
2. Dummy data
3. Missing data again. After handling dummy values
4. Data Labelling IDs
5. Data types
6. Merge dataframes
V: Exploratory Analysis
1. Describe on user data
2. Distribution of User Data by demographics variables
3. Distribution of Event Data
4. Distribution of Offer type
5. Data Processing: Filter only offer received
6. Distribution of Offers Received by Each Customer
7. Data Processing: Create columns of success or loss of Offers sent
8. How many offers were sent out, viewed and completed?
9. What type of offer has the best rate of completion?
10. What platform has the best rate of completion?
11. What offer has the best rate of completion?
12. Data Processing: Create columns of segmentations of Age and Income
13. Is there any relationship between demographic variables and rate of completion?
VI: Build a ML model to predict offer success
1. Data Processing
2. Modellings
3. Building the model of ML: pipeline and gridsearch
4. Evaluating the model
5. Saving the model
6. Running all models
7. Choosing the model
8. Feature Importance
9. Probability Offer Success
VII: Conclusion


## File Descriptions <a name="files"></a>
<pre>
<code>.
├── <b>README.md</b>
├── <b>starbucks_offers.ipynb </b> : notebook to run, with all development
├── <b>data</b> : It contains all data Files 
│ ├── <b>portfolio.json</b> :  containing offer ids and meta data about each offer (duration, type, etc.)
│ ├── <b>profile.json</b> :  demographic data for each customer
│ └── <b>transcript.json</b> :  records for transactions, offers received, offers viewed, and offers completed
├── <b>models.p</b>: all models are saved here
└── <b>requirements.txt</b>
 </code>
</pre>


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The Datasets used in this project are provided by Starbucks. And this is the final project of Udacity Data Science Nanodegree.
