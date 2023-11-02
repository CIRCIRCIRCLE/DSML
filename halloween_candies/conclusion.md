
## The dataset
Data was collected by creating a website where participants were shown presenting two fun-sized candies and asked to click on the one they would prefer to receive. In total, more than 269 thousand votes were collected from 8,371 different IP addresses.

The dataset comes from kaggle, the link is shown below: https://www.kaggle.com/datasets/fivethirtyeight/the-ultimate-halloween-candy-power-ranking/data

`Tools used:` Python, Flourish
`Knowledge contained:` Logistic Regression, Random Forest, Encoding numerical data

## Potential angles with this dataset:
Which candy is the most popular  
Which candy is the least popular  
Is candy containing chocolate more popular than candy without  
Which candy contains the most sugar, and does that impact its popularity  
Which qualities are associated with higher rankings?  
What’s the most popular candy? Least popular?  
Can you recreate the 538 analysis of this dataset?   

## Outline
1. Using python and machine learning method to do the prediction:  
    The main process contains:  
        data preprocessing;   
        use visualization tools to get the rough hints of the trend and relations;  
        Do the data modeling:  
            - `Logistic Regression:` Predict if a candy is chocolate or not based on its other features?  
            - `Random forest Classification:` Predict the win level of the candy  

2. Using flourish to do the visualization and story telling part  
