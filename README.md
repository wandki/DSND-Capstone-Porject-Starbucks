# DSND-Capstone-Porject-Starbucks


This is the capstone project for the Udacity Data Scientist nano-degree program. 

## Project Motivation
TODO

## Analysis Findings
TODO


## Technical information


### Installation
Run all py files with Python3. Make sure that you instal the following libraries using pip3 install command:
 - pandas
 - sklearn
 - plotly
 - .....


### Project File Structure
-- data: 
 -profile.json: Rewards program users 
    gender: (categorical) M, F, O, or null
    age: (numeric) missing value encoded as 118
    id: (string/hash)
    became_member_on: (date) format YYYYMMDD
    income: (numeric)

 -portfolio.json: Offers sent during 30-day test period 
    reward: (numeric) money awarded for the amount spent
    channels: (list) web, email, mobile, social
    difficulty: (numeric) money required to be spent to receive reward
    duration: (numeric) time for offer to be open, in days
    offer_type: (string) bogo, discount, informational
    id: (string/hash)

 -transcript.json: Event log
    person: (string/hash)
    event: (string) offer received, offer viewed, transaction, offer completed
    value: (dictionary) different values depending on event type
    offer id: (string/hash) not associated with any "transaction"
    amount: (numeric) money spent in "transaction"
    reward: (numeric) money gained from "offer completed"
    time: (numeric) hours after start of test
    
-- Starbucks_Capstone_notebook.ipynb: jupyter notebook


## Reference and Acknowledgements
The startbucks data that is used in this repository was provided by Udacity
