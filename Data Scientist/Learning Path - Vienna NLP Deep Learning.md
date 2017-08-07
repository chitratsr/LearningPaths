# Learning Path - Sentiment Analysis of Movie Reviews using Deep Learning with Vienna

## Audience: Data Scientist
## Type: Solution

### Summary
This solution provides an easy to use template to implement sentiment analysis using Word Embedding and Convolutional Neural Networks. 

### Lesson Path

| Objective |	Concept	| Technologies | Level | Pre-Requisites | Ignite Deliverable
| --- |	---	| --- | ---  | ---  | --- 
| Data preparation: Ingestion |  | Vienna | Intermediate | Python | Tutorial
| Data preparation: Data Cleaning and Merging | Using custom scripts functionality in the datasource wizard, perform deduping, resolve missing values and join datasets using Transforms feature of the datasource wizard | Vienna | Intermediate | Python | Tutorial
| Data preparation: Churn Labeling | Add column to perform label dataset (churners/non-churners) using either code snippet or GUI features of the datasource wizard | Vienna | Intermediate | Python | Tutorial
| Data Preparation: Feature Engineering | Generate derived features using 'Derive column by example' in the wizard or code snippets as scripts | Vienna | Intermediate | Python | Tutorial
| Experimentation and Model Building: Churn Classification | Integrate third-party libraries (such as scikit-learn and azureml) to develop regression and tree based classifiers for predicting churn | Vienna | Intermediate | Python (including external libraries) | Tutorial
| Experimentation and Model Building: Parameter Sweeps for Churn Classification | Perform parameter sweeps by triggering the execution from the previous step to identify "best model" | Vienna | Intermediate | Python | Tutorial
| Compare churn models | Evaluate different classifiers for predicting churn | Vienna | Intermediate | Python (including external libraries) | Tutorial
| Operationalization and consumption of Churn models | Deploy the churn models either either locally or remotely. Pass realtime commands utilizing az ml service | Vienna, Azure CLI , Azure Machine Learning CLI component | Intermediate | Python | Tutorial
