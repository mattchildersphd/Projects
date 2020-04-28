# Projects
Portfolio of Data Science Projects

Welcome to my portfolio of data science projects that I worked on in Thinkful's Data Science Flex program. I am including four of my four capstone projects here below.

[__Letting Americans Tell Us What They Think of Politicians *In Their Own Words*__](https://github.com/slackademic/Projects/blob/master/nlp_openended_anes.ipynb)
Using responses to the "likes" and "dislikes" questions about the presidential candidates, the open-ended ones that ask respondents about reasons why they might for or against the major party presidential candidates in the American National Election Studies (ANES), I use Natural Language Processing methods to what Americans think about the candidates. I use Bag of Words models to calculate the most popular positive and negative terms in peoples' considerations. I also compare how well several supervised learning models predict the sentiment of peoples' responses with Bag of Words and TF-IDF to vectorize the text. Finally, I use several topic models (LDA, LDA, NNMF) to cluster peoples' responses to see if we can extract useful labels if we want to code individual statements for analyses with other features from the surveys.
[Notebook: "nlp_openended_anes.ipynb"](https://github.com/slackademic/Projects/blob/master/nlp_openended_anes.ipynb)

    Data for the project are available from the American National Election Studies. ANES makes transcripts for open-ended   question responses available separately from the rest of the survey data. The data are publicly available, but you must   create an account with the ANES before downloading the data. Links for each year's data are below:
    - [2016 survey data and documentation](https://electionstudies.org/data-center/2016-time-series-study/)
    - [2012 survey data and documentation](https://electionstudies.org/data-center/2012-time-series-study/)
    - [2008 survey data and documentation](https://electionstudies.org/data-center/2008-time-series-study/)

[__Analyzing Requests for Government Services From Miami-Dade County Residents Using Unsupervised Learning Methods__](https://github.com/slackademic/Projects/blob/master/unsupervised_learning_capstone.ipynb)
I explored how local government segments its constituents by comparing how well several clustering algorithms perform in grouping data on requests for public services in Miami-Dade County (K-means, DBSCAN, Gaussian Mixture Models). Data for the project are available from the [Miami-Dade County Open Data Portal (311 Service Requests)](https://gis-mdc.opendata.arcgis.com/datasets/311-service-requests-miami-dade-county-2019).
[Notebook: "unsupervised_learning_capstone.ipynb"](https://github.com/slackademic/Projects/blob/master/unsupervised_learning_capstone.ipynb)

[__Predicting Unauthorized Status Among the United States's Noncitizen Population__](https://github.com/slackademic/Projects/blob/master/classifying_noncitizens_sipp2008.ipynb)
Using the best performing features found from a few of the most influential models in research estimating the size of the unauthorized immigrant population in the United States, I compared the performance of more than several supervised learning models in predicting unauthorized status among the noncitizen population using the 2008 Survey on Income and Program Participation. None of the models was very accurate and had either higher proportions of false negatives or false positives, which suggests that popular models used in missing data imputation algorithms have a lot of room for improvement. Data are available from the [U.S. Census Bureau](https://www.census.gov/programs-surveys/sipp/data/2008-panel.html).
[Notebook: "classifying_noncitizens_sipp2008.ipynb"](https://github.com/slackademic/Projects/blob/master/classifying_noncitizens_sipp2008.ipynb)

[__Which Political Campaigns Are Advertising on Google's Platforms in 2019?__](https://github.com/slackademic/Projects/blob/master/exploring_google_political_ads.ipynb)
An exploration of which federal, state, and local campaigns are using Google's platforms for digital political advertising in 2019, an "off-off year." Data are from [Google's advertising transparency report](https://transparencyreport.google.com/political-ads/region/US?hl=en.). 
[Notebook: "exploring_google_political_ads.ipnyb"](https://github.com/slackademic/Projects/blob/master/exploring_google_political_ads.ipynb)



