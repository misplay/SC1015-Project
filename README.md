# SC1015 FCSE Group 4 Mini Project

## Overview

This is our Mini-Project for SC1015 - Introduction to Data Science and Artificial Intelligence.

We as a group have noticed our friends who are students having increasingly more mental health issues. After reading an article from the straits times, we had an epiphany that social media could be one of the leading factors of this, as apps like TikTok, Instagram, Facebook become more mainstream. 

## Problem Definition

- How do you know if your mental health is affected by overuse of social media, and what are the potential interventions to tackle the problem?

## Dataset

The Social Media and Mental Health dataset by Kagge user SOUVIKAHMED071 is a recent dataset (Made in July 2023). It is described as a user-surveryed dataset, to allow for users to know if they should seek professional help.

## Data analysis techniques

After the cleansing of our dataset, through balancing the user's inputs, removing of unnecessary data, we begin our data analysis, where we explore the relationship between time spent and each variable. More details can be found within our Notebook.

We have done the following to prepare our data:
- [Data Normalisation] - Normalising the participant feedback from the dataset
- [Data Renaming] - Ensuring variables are more understandable

To perform our data analysis  so, we have utilised the following data analysis algorithms:
- Chi Squared Test: The significance level represents the threshold at which you're willing to reject the null hypothesis.
- K-Modes Algorithm: The K-modes algorithm is a clustering technique used to group data points with similar characteristics, especially when dealing with categorical data.

## Solutions
#### Support vector machine
The first model we have implemented is the Support vector machine, which we have made use from sklearn library. This is a supervised mmachine learning algorithm that will find an optimal line in order to classify our data based off the clustering done during our K-Modes Algorithm. 

On training the model, we visualise the decision process of the Decision Tree Classifier using a tree diagram.

After testing for accuracy, we have a 90.2% accuracy on our model. Please do try out our model, where we have provided it on the notebook.

#### Logistic Regression

The second model we have made use of is the Logistic Regression model, existing in the sklearn library. Making use of multinomial logistic regression, because we have six dependent variables as determined in our Chi squared test. This has allowed us to find out that Mindless scrolling and Restlessness are 2 factors that are strongly linked to time spent on social media. By reducing your time spent on social media, it will mean that you will directly reduce your mindless scrolling frequency. 

Our Logistic Regression model has an accuracy attained of 42.11%.

## Conclusion

From the results of the project, we now have a working model to allow for users to know if they are affected by too much social media usage, and what are the 2 largest afffectors corelated to time spent on social media. We have provided recommendations within the notebook as well. We also came out with possible future recommendations, which could include making use of technologies like Ensemble from sklearn to improve our model

## What did we learn from this project?

- Chi Squared test from scipy 
- K-Modes from Kmodes
- Logistic Regression from sklearn
- Support Vector Machine from sklearn
- Normalising values

## Contributions

- [Bryan](https://github.com/misplay)  - Support Vector Machine, Logistic regression
- [Douglas](https://github.com/eld0ude) - K-Modes Algorithm, Chi Square Test
- [Zhongyuan](https://github.com/davidli1127) - Dataset analysis, Dataset cleanup, balancing

We have worked together on everything else ranging from slides, to research.

## References <br />
[1] https://www.straitstimes.com/opinion/smartphones-and-social-media-are-destroying-children-s-mental-health <br />
[2] https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health<br />
[3] https://www.geeksforgeeks.org/python-pearsons-chi-square-test/  <br />
[4] https://medium.com/@reddyyashu20/k-means-kmodes-and-k-prototype-76537d84a669<br />
[5] https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/<br />
[6] https://www.datasklr.com/logistic-regression/multinomial-logistic-regression <br />
