# LLM Project

## Project Task
This project involves creating a sentiment analysis tool that interprets IMDB movie review sentiments and classifies it as either positive(1) or negative(0). The tool uses a LLM from Huggingface that is pretrained for movie sentiment analysis, which is then fine tuned and optimized. The model's performance is compared with a baseline Logistic Regression model. 
## Dataset
The dataset used for training is IMDB `train` dataset from the datasets library. It contains 25000 rows of movie reviews and its asspciated label (1 or 0). The data is preprocessed by removing `<br />` HTML tags, replacing punctuation with empty space (except apostrophe), and standardizing to lower case. The baseline Logistic Regression model was trained on all datapoints, and 400 datapoints were selected for the training and evaluation of the fine-tuned model.    

## Pre-trained Model
I selected the `Moview_review_sentiment_analysis_model` (Model ID 1883864250) from `JamesH` as my pre-trained model to fine tune. 

## Performance Metrics
As the model performs a binary classification tasks, the classification metrics used for evaluation are as follows: 

- accuracy
- f1
- recall
- precision
- AUC



## Hyperparameters
The hyperparameter that optimized the model was the learning rate 
