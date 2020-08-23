# Unlabeled Mail Classification and Prioritization

## Problem Statement
- Classify unlabeled french mails data based on product category, prioritized them based on customer urgency.
- Generate mail templates as per the product for top priority mails.

## Approach
- Different GCP services were used in the development of the project. 
- BigQuery is used for importing and exporting the datasets
- Cloud Translation is used for translating between English and French texts.
- Cloud Natural Language API is used for sentiment analysis, entity detection.
- Sentiment Analysis is used to calculate the Sentiment score, which help us in finding the top priority mails.
- Labelling is done using entity detection. 
- Cloud AI Platform is used for training on different classification algorithms.

## Code
- [Final Processed code](https://github.com/ayushagg31/PPH-1/blob/master/UI-integration.ipynb)
- [Tags generated for labelling](https://github.com/ayushagg31/PPH-1/blob/master/Mails_tags_dictionary.txt)
