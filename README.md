


# README Template

# Grand Slam Analysis
## Alejandro & Chun
## Data Analytics Barcelona Feb to Apr 2019]

### Overview

The project aims to identify the most important statistics which determine the result of 
the Grand Slam games and predict the result of two upcoming tournaments.

* What data/business/research/personal question you would like to answer?
Make sure the question description is human-friendly because you will have non-tech audience to see your final project presentation.

A brief intro of the game is given followed by the 3 most important statistics. 
Data like physical measures of players and statistics of past tournaments and rankings are all taken into account in our analysis. 

Then the next step is prediction specific to clay court tournaments. Since Monte Carlo and French Open is played in April and May every year. An analysis showing correlation of performance in the prior and that to the later will be performed. Besides, a prediction model will be built to predict winner of the two tournaments.

Hypothesis Test:
Ideas: 
Players who have higher breakpoints saved percentage will always win the game
Players who has significantly more aces will win the game
Player who have more double fault will lose the game
The number of ace is higher in hard/grass than on clay



* Did you understand the context for the question and the scientific or business application?


* What is the hypothesis you would like to test in order to answer your question?
Frame your hypothesis with statistical/data languages (i.e. define Null and Alternative Hypothesis). You can use formulas if you want but that is not required.


* Did you consider whether the question could be answered with the available data?


* How will you test your hypothesis?
* How will you test your success?


### Data Preparation
Overview:
* What is your dataset about?
* Where/how did you obtain your dataset?

The dataset contains 103 csv files of the past ATP matches, qualifiers and future games record from year 1968 up to 2018. Each columns in csv files contains stats of one match from 32/64 up to finals in absolute figures. Both winner and loser data is recorded in the same row.

[Kaggle dataset](https://github.com/awesomedata/awesome-public-datasets#timeseries)

It can be either a public dataset or collected with API/web scraping.
Provide a link if possible.
* General description of the dataset such as the size, complexity, data types, etc.

### Data Ingestion & Database
* If you downloaded a dataset (either public or private), describe where you downloaded it and include the command to load the dataset.
* If you obtain the data via API/web scraping, provide the scripts.
* Provide a schema of your tables.

### Data Wrangling and Cleaning
Your full process of data wrangling and cleaning.
* Document your workflow and thinking process.

### Data Analysis
* Overview the general steps you will go through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Print charts to demonstrate the effect of your work. Charts make your presentation look good too.
* If you use ML in your final project, also describe your feature selection process.

### Model Training and Evaluation
* Train your ML model, produce results, and evaluate.
Random Forest Classifier
Logistic Regressions

* This is an iterative process. Try your best to improve your model performance by:
  * Try different models and select one that is the simplest yet produce the best result.
  * Try advanced techniques and see if they improve the result.

### Conclusion
* Summarize your data analysis result.
* State your conclusion of your hypothesis testing.
* Interpret your findings in terms of the human-understandable question you try to answer.

### What are the next steps?


