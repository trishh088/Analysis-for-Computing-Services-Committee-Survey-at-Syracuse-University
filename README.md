# Analysis-for-Computing-Services-Committee-Survey-at-Syracuse-University

The University Faculty Senate's Computing Services Committee asked faculty and staff to respond to an online survey about campus computing services and technology. The survey ran from the end of September to mid-October 2022, with a response rate of nearly 30%. Most of the questions were Likert Scale questions (multiple choice ranging from agree to disagree), but also included several free text boxes. Like any survey, most people didn’t fill out all the sections involving text fields. Using text mining tools as our data analysis toolkit, our task was to understand which computing services was doing well and what were the areas of improvement. The results were then reported back to the University Senate, who maintains Syracuse University’s computing resources.

## About the Data
The technologies for which feedback was collected involved all kinds of tools or resources used by the faculty to teach students. 
They were as follows: 
MySlice, Wireless Network, Zoom, Teams, Blackboard, Kaltura, Teaching Tools, Assistive Tools, Accessibility Feedback, IT Challenges, Security, Playposit, Google Suite. Table X below has the list of user satisfaction rate. 

## Methology
Given the fact that optional text boxes appeared in the survey only when someone was dissatisfied with a service, we chose to perform sentiment analysis for a technology only if there was sufficient feedback to build a model (by checking the count of non-null values for each technology/service). For the rest we used text mining approaches such as word cloud, frequency distribution using count and TF-IDF, and cluster analysis using BERT to analyze the feedback. We created functions for word clouds, TF-IDF, BERT and sentiment analysis to ease our search for those services whose improvement might have the greatest positive impact on the work lives of Syracuse University faculty.

## Ethics Statement
Since we didn’t have any personally identifiable information regarding the survey and the fact that this survey would help improve the experience of users, there were no ethical concerns. 

## Conclusion
Below are the insights and recommendations we got based on the data we were provided for this survey:
1)	Blackboard seems to be the tool that most users are unsatisfied across the feedback such as IT challenges, Teaching Tools. They would prefer to use Canva, are not happy with the UI of the tool and find it hard to grade on the tool. 
2)	Another tool that users are highly unhappy with was MySlice. They are unhappy with the UI, the fact that they need to re-navigate to a page again and again, have to see the student page first and then navigate to the faculty page each time and would prefer to be able to bookmark or customize the UI to better suit their needs and are highly unhappy with the stale login issues faced. Unhappiness for this tool was again seen across multiple tools feedback.
3)	Troubleshoot and see if the bandwidth for wireless network is tested for classrooms in Life science building and near College Place bus stop.
4)	People have a hard time finding information regarding accessibility and would like to have someone dedicated to this cause so that they can incorporate the policy in their work such as marketing & business presentations
5)	Users find Answers.com confusing and cumbersome to navigate.
6)	Users would like a bigger team for the support staff and have recommended to either increase the salary of the support staff or hire more people to get their queries answered sooner.


## Reference
•	https://medium.com/@piocalderon/vader-sentiment-analysis-explained f1c4f9101cd9#:~:text=VADER%20sentiment%20analysis%20combines%20a,movie%20reviews%20and%20opinion%20articles.
