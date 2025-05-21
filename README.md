# Prodigy_DS_Task-02

Welcome to the Titanic Survival Analysis project! This project was done under prodigy infotech. This project provides an exploratory data analysis (EDA) of the Titanic dataset using Python. The goal is to gain insights into the factors that influenced survival rates during the tragic sinking of the Titanic. Below, we provide a detailed overview of the code and its components. 🌊🔍

## Overview

The project consists of three main datasets: train.csv, test.csv, and gender_submission.csv. The train.csv dataset is used to train the model and perform the EDA, while the test.csv dataset is used to test the model's performance. The gender_submission.csv file provides a sample submission format.

Dataset Example: https://www.kaggle.com/c/titanic/data

# Exploratory Data Analysis (EDA) 📊

## 1. Data Loading and Basic Information 📥
First, we load the datasets using pandas and display basic information, such as the data types and summary statistics. This helps us understand the structure and contents of the datasets.

![image](https://github.com/user-attachments/assets/382e3cda-0b39-4638-8824-298a51c9c1e2)
![image](https://github.com/user-attachments/assets/82160b6c-f574-4314-8c4b-a630a43a5f21)
![image](https://github.com/user-attachments/assets/6606b41b-cb4c-4399-98f6-7317910ab0b0)
![image](https://github.com/user-attachments/assets/036a9e3a-ecd3-460b-b338-4d19e1759ea6)
![image](https://github.com/user-attachments/assets/f76524f9-ce92-4ceb-8e4b-6e41b43d40b3)

## 2. Data Inspection and Missing Values 🔍
We inspect the first few rows of each dataset and check for missing values. This step is crucial for data cleaning and preprocessing

![image](https://github.com/user-attachments/assets/cb4e4b65-e8ea-4fea-9f50-8c3af33cd6d6)
![image](https://github.com/user-attachments/assets/c98bc3fd-1b65-4450-932b-d9d2c3f9399a)
![image](https://github.com/user-attachments/assets/10181bcb-1ef5-4d00-bd8f-d8f394590d6d)
![image](https://github.com/user-attachments/assets/d610893f-21a3-4e08-b472-f02fa2aebcd7)
![image](https://github.com/user-attachments/assets/e853f1c0-06b1-402a-8f6f-bb7c848a6f7c)

## Making the Report

![Screenshot 2025-05-21 233337](https://github.com/user-attachments/assets/d059c650-c86b-4349-9c34-9cf51f94f832)
![image](https://github.com/user-attachments/assets/f5c53e74-9cf7-4381-8d6d-1a279949cf7b)
![image](https://github.com/user-attachments/assets/287dc04c-23db-4a93-b0d7-e48b2a34ae8a)
![image](https://github.com/user-attachments/assets/5665fed3-953c-4256-8919-addd8065ed6f)

## 3. Visualizations and Insights 📈
We use Seaborn and Matplotlib to create various visualizations to uncover patterns and relationships in the data. The visualizations include:

![image](https://github.com/user-attachments/assets/2256ddc6-6857-4c6d-8ef1-ba4526da325b)
![image](https://github.com/user-attachments/assets/a7dd43e6-7b4c-40d5-b0ed-6c096584e0e6)
![image](https://github.com/user-attachments/assets/2aa0a39f-6184-466e-b0f9-3c50aea6a046)
![image](https://github.com/user-attachments/assets/353ee55f-f63d-4c53-bcb4-7d70ac60776f)
![image](https://github.com/user-attachments/assets/c4c281e8-f65c-4574-a39f-224337d2fafc)
![image](https://github.com/user-attachments/assets/3c183403-726c-48e9-a452-c8c99b49c6c3)

 Age Distribution: A histogram to visualize the distribution of passengers' ages.

![image](https://github.com/user-attachments/assets/acbd6dfc-ca34-4b82-ba64-056603126ce2)

Survival Count: A count plot showing the number of survivors and non-survivors.

![image](https://github.com/user-attachments/assets/707f4435-7f18-4388-98e7-dcca1f7f9cab)

Passenger Class vs. Survival: A count plot showing survival rates by passenger class.

![image](https://github.com/user-attachments/assets/faf49f91-bbf7-440a-9bb2-4a5d06d461fc)

Sex vs. Survival: A count plot showing survival rates by gender.

![image](https://github.com/user-attachments/assets/e6625daa-2962-4d17-b56e-8b8039bf4015)

Fare Distribution: A histogram to visualize the distribution of fares paid by passengers.

![image](https://github.com/user-attachments/assets/9c596c08-47da-4e07-aa00-5ce9821004ef)

Age vs. Passenger Class: A box plot to show the age distribution across different passenger classes.

![image](https://github.com/user-attachments/assets/e0cacb14-dd88-48b2-b8f3-0cc60a9e8a97)

