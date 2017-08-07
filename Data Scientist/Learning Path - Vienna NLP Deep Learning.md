# Learning Path - Sentiment Analysis of Movie Reviews using Deep Learning with Vienna

## Audience: Data Scientist
## Type: Solution

### Summary
This solution provides an easy to use template to implement sentiment analysis using Word Embedding and Convolutional Neural Networks. 

### Lesson Path

| Objective |	Concept	| Technologies | Level | Pre-Requisites | Ignite Deliverable
| --- |	---	| --- | ---  | ---  | --- 
| Data Preparation: Ingestion |Ingest IMDB reviews along with labelled sentiment | Vienna | Intermediate | Python (keras datasets) | Tutorial
| Data Understanding: Review Statistics | Obtain review statistics using the datasource wizard with Vienna | Vienna | Intermediate | Python | Tutorial
| Data Understanding: Review Encoding | Encode each review as a sequence of word indexes | Vienna | Intermediate | Python | Tutorial
| Modeling: Word Embedding | Generate a word embedding representation for the review dataset | Vienna | Intermediate | Python | Tutorial

| Experimentation and Model Building: Churn Classification | Integrate third-party libraries (such as scikit-learn and azureml) to develop regression and tree based classifiers for predicting churn | Vienna | Intermediate | Python (including external libraries) | Tutorial
| Experimentation and Model Building: Parameter Sweeps for Churn Classification | Perform parameter sweeps by triggering the execution from the previous step to identify "best model" | Vienna | Intermediate | Python | Tutorial
| Compare churn models | Evaluate different classifiers for predicting churn | Vienna | Intermediate | Python (including external libraries) | Tutorial
| Operationalization and consumption of Churn models | Deploy the churn models either either locally or remotely. Pass realtime commands utilizing az ml service | Vienna, Azure CLI , Azure Machine Learning CLI component | Intermediate | Python | Tutorial
