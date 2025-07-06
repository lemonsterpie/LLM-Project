# LLM Project

## Project Task
This is a sentiment analysis tool that interprets IMDB movie review sentiments and classifies it as either positive (1) or negative (0). The tool is a LLM that is finetuned and optimized based on a pretrained HuggingFace model for movie review sentiment analysis. The model's performance is evaluated by classification metrics, then compared with a baseline Logistic Regression model as well as the pretrained model before finetuning and optimization. 

## Dataset
The dataset used for training is the IMDB `train` dataset from the datasets library. It contains 25000 rows of movie reviews and its associated label (1 or 0). The data is preprocessed by removing `<br />` HTML tags, replacing punctuation with empty space (except apostrophe), and standardizing to lower case. The baseline Logistic Regression model was trained on all datapoints, and 200 datapoints each were selected for the training and evaluation of the fine-tuned model.    

## Pre-trained Model
I selected the `Moview_review_sentiment_analysis_model` (Model ID 1883864250) from `JamesH` as my pre-trained model to fine tune. 

## Performance Metrics
As the model performs a binary classification task, the classification metrics used for evaluation are as follows: 

- accuracy
- f1
- recall
- precision
- AUC

Logistic Regression model 

![Logistic Regression Eval Metrics](images/logreg_model.JPG)

Pretrained model before finetuning and optimization 

![pretrained model eval metrics](images/pretrained_eval.JPG)

Final evaluation metrics deployed: 

## Hyperparameters
The hyperparameter that optimized the model was the learning rate 
