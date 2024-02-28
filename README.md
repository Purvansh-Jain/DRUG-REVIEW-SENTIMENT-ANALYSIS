# Drug Review Sentiment Analysis Using LSTM

## Project Overview
This project utilizes Long Short-Term Memory (LSTM) networks, a type of recurrent neural network, for the sentiment analysis of drug reviews. The goal is to classify sentiments expressed in drug reviews, ranging from positive to negative, to provide insights into patient experiences with medications.

## Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)

## Introduction
This study employs LSTM algorithms in Natural Language Processing (NLP) to conduct sentiment analysis on drug reviews, aiming to enhance pharmaceutical insights and patient care. The model achieves an accuracy of 86% in sentiment categorization, providing a solid foundation for nuanced sentiment analysis in healthcare.

## Technologies Used
- Python
- LSTM (Long Short-Term Memory)
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for model evaluation
- Jupyter Notebook for code development and presentation

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository and encompasses patient reviews on specific drugs, associated conditions, and a 10-star patient satisfaction rating system. The dataset's structure is as follows:

- **Entries:** 161,297
- **Features:** 7 (drugName, condition, review, rating, date, usefulCount)

### Key Highlights
- **Drug Name:** Name of the medication.
- **Condition:** Medical condition treated.
- **Review:** Textual patient feedback.
- **Rating:** 10-star satisfaction rating.
- **Date:** Date of review submission.
- **Useful Count:** Number of users who found the review helpful.

The primary challenge was the absence of explicit sentiment labels within the dataset, requiring the derivation of sentiments from the given ratings to serve as the target variable for sentiment analysis. This process enables a deeper dive into patient experiences and satisfaction levels, offering crucial insights for healthcare improvement.


## Installation
Instructions on setting up the project environment.
```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
```

## Usage
Guide on how to use the project, including running the Jupyter notebook, viewing the presentation, and exploring the dataset.

## Results
The LSTM model achieved an 86% accuracy in classifying drug review sentiments. The findings offer valuable insights for pharmaceutical companies and healthcare providers.

## Contributors
- Purvansh Jain

## Acknowledgments
Special thanks to all the contributors to the datasets and technologies used in this project.

## License
[MIT](LICENSE)