# Hear Us: Toward a More Just World

## ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 5: Web APIs & NLP

### Problem Statement

With an average of over 600 noteworthy protests occurring globally per year, and just 10% succeeding in achieving a positive government response toward their aims, international human rights organizations face a dismal kind of triage. Where can we devote resources to greatest effect, and where will they be wasted? How can we turn a failure into a success?

We seek to leverage extensive data, compiled by the CIA, on the demographics of hundreds of nations and the thousands of mass movements that have arisen over the past two decades and change, in building a highly-interpretable predictive model of protest success. The insights gained from machine learning will inform Amnesty International's budgeting of both efforts and funds to new movements as they unfold.

Furthermore, state-sanctioned violence is an all-too common response to popular movements. Independently of our predictions of success, we will indentify indicators of which protests are most vulnerable to violence at the hands of state actors. By predicting this in advance, we enable Amnesty to direct media attention before violence erupts -- often the most effective way to prevent it.


### Executive Summary 

Using a logistic regression model, we are able to predict protest success with 94.9% accuracy.  We identify several key factors in protest outcome based on feature coefficients, K-means clustering, and digging down on several aspects of the dataset.  Results are broken down by region, protestor identity, reason for protest, and Government type, among others.  Furthermore, indicators of state violence are picked out for further examination.

### Table of Contents
- Problem Statement
- Imports
- Munging
- Functions
- EDA
- Modeling
- Model Results
- Conclusions and Recommendations

### Data 

Primary data came from the [Mass Mobilization Project](https://massmobilization.github.io/).  The project is sponsored by the Political Instability Task Force (PITF), which is in turn funded by the Central Intelligence Agency.  The views expressed by the PITF and Principle Investigators are their own, and not endorsed by the CIA or US Government.

To supplement this information, the [CIA World Factbook](https://www.cia.gov/the-world-factbook/) was brought in as well.  

Both datasets were compiled according to the interests of the CIA and thus, unfortunately, do not include any US data.  They are, however, both extremely robust datasets, offering a plethora of meaningful features for investigation.

### Toolset

- Standard data science tools:
- - pandas
- - numpy
- - seaborn
- - matplotlib
- sklearn 
- keras
- nltk
- Word2Vec
- transformers
- SMOTE
- Tableau

### Visualizations

- [Annual Global Protests](https://public.tableau.com/profile/david.holcomb#!/vizhome/Project_5_protests/AnnualGlobalProtests?publish=yes)
- [Accommodation of Protesters by Country](https://public.tableau.com/profile/david.holcomb#!/vizhome/Project_5_protests/AccomodationofProtestorsbyCountry)
- [Global Protests per Year & Outcomes](https://public.tableau.com/profile/david.holcomb#!/vizhome/Project_5_protests/GlobalProtestsperYearOutcomes?publish=yes)
- [Images](./noah/images)
