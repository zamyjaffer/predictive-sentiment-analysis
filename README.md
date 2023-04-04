# Analyzing the Impact of Sentiment Expressed in Article Titles on their Share Volume
This GitHub repository contains a data science project conducted by me during my General Assembly part-time data science course in 2021. The project's main aim was to investigate whether the sentiment expressed in article titles published over the last three years had an impact on the volume of shares an article received.

## 1. Project Proposal
The project's problem statement was "Does the sentiment expressed in article titles published over the last 3 years have an impact on the volume of shares an article receives?". I proposed to engineer a dataset to test this hypothesis using the Google Analytics API to extract article titles and their share volume data from a client's content hub, which I had access to. I then incorporated it with the Adoreboard API to analyze each article title for the 24 different states of emotion, indexed with a score from 1 to 100, indicating sentiment. The 24 emotion columns would form our covariates, and the share data would be the response.

## 2. Project Data and Exploratory Data Analysis (EDA)
In the first step, I engineered the dataset by extracting data from the Google Analytics API and incorporating it with the Adoreboard API's data. I then conducted an exploratory data analysis (EDA) to explore the data and understand it better. I did this using Jupyter Notebook and Python libraries such as Pandas, Numpy, and Matplotlib. In the EDA stage, I examined the data's distribution, checked for missing values and outliers, and identified any potential relationships between the variables.

## 3. Technical Notebook
After completing the EDA, I created a technical Jupyter Notebook that details the whole analysis, including the problem, dataset, analysis, and findings. The technical notebook contains all the code used in the project and detailed explanations of each step.

## 4. Project Presentation
I created a PowerPoint presentation that runs through the analysis including' the problem, methodology, findings, and implementations. The presentation provides a comprehensive overview of the project and highlights the critical findings that could inform the client's content creation strategy.
