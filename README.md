<img src="kaggle_image.jpg" style="width:1000px; height:500px"/>


# Kaggle Data Science - Machine Learning Survey 2017
##  Author: Jaekyung Lee

### Methodology
- This survey received 16,716 usable respondents from 171 countries and territories. If a country or territory received less than 50 respondents, we grouped them into a group named “Other” for anonymity.
- We excluded respondents who were flagged by our survey system as “Spam” or who did not answer the question regarding their employment status (this question was the first required question, so not answering it indicates that the respondent did not proceed past the 5th question in our survey).
- Most of our respondents were found primarily through Kaggle channels, like our email list, discussion forums and social media channels.
- The survey was live from August 7th to August 25th. The median response time for those who participated in the survey was 16.4 minutes. We allowed respondents to complete the survey at any time during that window.
- We received salary data by first asking respondents for their day-to-day currency, and then asking them to write in either their total compensation.
  - We’ve provided a csv with an exchange rate to USD for you to calculate the salary in US dollars on your own.
  - The question was optional
- Not every question was shown to every respondent. In an attempt to ask relevant questions to each respondent, we generally asked work related questions to employed data scientists and learning related questions to students. There is a column in the schema.csv file called "Asked" that describes who saw each question. - You can learn more about the different segments we used in the schema.csv file and RespondentTypeREADME.txt in the data tab.
- To protect the respondents’ identity, the answers to multiple choice questions have been separated into a separate data file from the open-ended responses. We do not provide a key to match up the multiple choice and free form responses. Further, the free form responses have been randomized column-wise such that the responses that appear on the same row did not necessarily come from the same survey-taker.

### Dataset
The data includes 5 files:
- `Kaggle-Survey-2017-ML-DS.ipynb`: a main Jupyter Notebook file that includes data wrangling, analysis and data visualization.
- `schema.csv`: a CSV file with survey schema. This schema includes the questions that correspond to each column name in both the `multipleChoiceResponses.csv` and `freeformResponses.csv`.
- `multipleChoiceResponses.csv`: Respondents' answers to multiple choice and ranking questions. These are non-randomized and thus a single row does correspond to all of a single user's answers. -freeformResponses.csv: Respondents' freeform answers to Kaggle's survey questions. These responses are randomized within a column, so that reading across a single row does not give a single user's answers.
- `conversionRates.csv`: Currency conversion rates (to USD) as accessed from the R package "quantmod" on September 14, 2017
- `RespondentTypeREADME.txt`: This is a schema for decoding the responses in the "Asked" column of the schema.csv file.

### Questions:
1. Python or R?
2. What data science tools and methods are going be in the limelight?
3. Where should I learn Data Science?
4. Do I need a 'high-performance' computer to study Data Science?
5. How many hours should I study?
6. What blogs, Podcasts, classes are recommended for DS?
7. How much do data scientists make?
8. Where can I get data from?
9. How do data scientist spend most of their time at work?
10. What job skill is most important?


### Summary of Findings
- Python is mainly used by most participants who are working in DS-ML industry
- Following tools will be in the limelight: TensorFlow (23%), Python (15%), R (8%), Clouds: Amazon ML, Google Cloud Computing, MS Azure ML, IMB Watson
- Deep Learning, Neural Nets, Times Series Analysis, Baysean Methods will be popular
- People recommended Kaggle the most to learn DS, however, this survey result was hosted in Kaggle, so the result might be biased
- Macbook users, labto + Cloud service, Azure, and gaming labtop with capable GPU are good enough to study or work in DS-ML industry
- Full time workers (780+) mostly study for 2-10 hours a day
- Most of job seekers (850+) study 2-10 hours
- The proportion of job seekers (400+) studying 11-39 hours is much higher than full-time workers, only 150+ studying 11-39 hours
- Data Scientists and Machine Learning Scientists in the United States make $115,689 on average, which is more than twice of national mean $53,812
- The most popular dataset source is Socrata, Kaggle, data.world, and google search followed
- DS spend 37% of their time for data gathering. They also spend a lot of time to build models, create visualizations, and find insights.
- Python, statistics knowledge, skills in visualization, SQL, and R are very necessary
- MOOC, KaggleRanking, EnterpriseTools, Degree are nice to have (to find a job or develop careers)
