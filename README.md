# Starbucks Capstone Porject


This is the capstone project for the Udacity Data Scientist nano-degree program. 

## Project Motivation
Sending offers to customer is a good strategy to attract new customers and retain existing one. However, not all customers respond in a similar way and individual customers have their own preferences towards received offer types. A customer might be interested in saving money with discounts, another might be more interested in getting more items for less while a different customer would prefer to only know about what is new without caring for any savings. This brings us to the topic of this article and we starting with our problem statement:
We aim to identify Starbucks customers behavior in regards to sent offers. This include analyzing and grouping Starbucks customers to provide customized offers that has higher chance of attracting and retaining customers and influencing their purchases.

## Analysis Findings
Analysis findings are documented in the following meduim [article](https://waadyk.medium.com/starbucks-offers-data-analysis-48e75a379a95)


## Technical information


### Installation
Run all py files with Python3. Make sure that you instal the following libraries using pip3 install command:
* pandas
* numpy
* math
* json
* matplotlib
* sklearn:
  * train_test_split
  * AdaBoostClassifier
  * GaussianNB
  * DecisionTreeClassifier
  * RandomForestClassifier
  * Aaccuracy_score


### Project File Structure
* **data** 
  * **profile.json:** Rewards program users 
    * gender: (categorical) M, F, O, or null
    * age: (numeric) missing value encoded as 118
    * id: (string/hash)
    * became_member_on: (date) format YYYYMMDD
    * income: (numeric)

  * **portfolio.json:** Offers sent during 30-day test period 
    * reward: (numeric) money awarded for the amount spent
    * channels: (list) web, email, mobile, social
    * difficulty: (numeric) money required to be spent to receive reward
    * duration: (numeric) time for offer to be open, in days
    * offer_type: (string) bogo, discount, informational
    * id: (string/hash)

  * **transcript.json:** Event log
    * person: (string/hash)
    * event: (string) offer received, offer viewed, transaction, offer completed
    * value: (dictionary) different values depending on event type
    * offer id: (string/hash) not associated with any "transaction"
    * amount: (numeric) money spent in "transaction"
    * reward: (numeric) money gained from "offer completed"
    * time: (numeric) hours after start of test
    
* **Starbucks_Capstone_notebook.ipynb:** jupyter notebook


## Reference and Acknowledgements
The startbucks data that is used in this repository was provided by Udacity
