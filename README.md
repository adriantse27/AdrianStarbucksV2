
Thank you Starbucks for Providing the data.

Objective
To Solve Starbucks's Challenge of finding the right offer to send to its customers using Data Science.
This will maximize the use of Starbucks marketing strategies and maximize their profit/revenue compared to before when they were sending unpersonalized offers to everyone at the same time using the same offer.

Methodology
1. Clean the Data
2. Process the Data using one hot encoding and other methodologies
3. Explore the Data
4. Implement Prediction Model
5. SVD
6. Evaluation
7. Creating the recommendation engine based on th data retreived from Recommendation model
8. Finally recommending offer based on type of customer

Data set
portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

portfolio.json

id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)
profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income
transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record


Libraries used
Pandas
Numpy
Math
Json
matploylib.pyplot
Datetime
Pickle


Instructions
The pickle files are actually saved in the folder, if we want to skip the process of creating the matrix, we can use the pickle files to run quicker.

Medium Blog Post Link: https://unstoppablebird.medium.com/the-starbucks-offer-you-crave-most-cff74a9e5739
