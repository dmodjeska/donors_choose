## Introduction

During the period March-April 2018, Kaggle held a competition called [DonorsChoose.org Application Screening](https://www.kaggle.com/c/donorschoose-application-screening). The goal was to predict whether teachers' project proposals were accepted by DonorsChoose.org, a non-profit organization. A full description of this competition is below. 

For processing the data, feature engineering and word vectorization (using TF-IDF) were used. For modeling the data, feature selection and XGBoost generated reasonable predictions.

## Description of Competition (from Kaggle Site)

Founded in 2000 by a high school teacher in the Bronx, DonorsChoose.org empowers public school teachers from across the country to request much-needed materials and experiences for their students. At any given time, there are thousands of classroom requests that can be brought to life with a gift of any amount.

DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. Right now, a large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.

Next year, DonorsChoose.org expects to receive close to 500,000 project proposals. As a result, there are three main problems they need to solve:

How to scale current manual processes and resources to screen 500,000 projects so that they can be posted as quickly and as efficiently as possible

How to increase the consistency of project vetting across different volunteers to improve the experience for teachers

How to focus volunteer time on the applications that need the most assistance

The goal of the competition is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.

With an algorithm to pre-screen applications, DonorsChoose.org can auto-approve some applications quickly so that volunteers can spend their time on more nuanced and detailed project ​vetting processes, including doing more to help teachers develop projects that qualify for specific funding opportunities.

Your machine learning algorithm can help more teachers get funded more quickly, and with less cost to DonorsChoose.org, allowing them to channel even more funding directly to classrooms across the country.

## Code

* [Data Processing](https://github.com/dmodjeska/donors_choose/blob/master/teachers_processing_21May2018.ipynb)
* [Data Modeling](https://github.com/dmodjeska/donors_choose/blob/master/teachers_modeling_21May2018.ipynb)

