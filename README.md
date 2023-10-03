# Spam Text Message Classification Project

## Overview
This project focuses on building a machine learning model to classify text messages as either spam or non-spam (ham). 
The goal is to develop an accurate and efficient classifier that can automatically identify and filter out spam messages, improving user experience and privacy.


## Project Objective
The main objective of this project is to build a text classification model that can distinguish between spam and non-spam text messages. The model will be trained using a labeled dataset, and its performance will be evaluated based on various metrics to ensure its effectiveness.

## Dataset
The dataset used for training and evaluation contains labeled text messages, where each message is categorized as either spam or non-spam (ham). 
The dataset will be split into training and testing sets to train and validate the model's performance.
You can download the dataset from here.
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## Project Structure
The project directory structure is organized as follows:
```
|-- README.md
|-- spam.csv
|-- ipynb
```

- `README.md`: Provides an overview of the project and how to use it.
- `ipynb/`: Contains the code for cleaning,training and evalution. 
- `.csv/`: Contains the dataset file.


## Setup
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd spam-text-message-classification
   ```

## Usage
To use the model for classifying text messages as spam or non-spam, follow these steps:
1. cleaning and Training the model using the provided dataset (refer to [ipynb])).
2. Use the trained model for predicting spam or non-spam text messages in your application.
```
