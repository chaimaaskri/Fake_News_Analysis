# NLP Fake News Analysis - v1.1

## Short Repo Description

**NLP Fake News Analysis**  
A machine learning-based project to detect fake news using natural language processing (NLP) techniques. The model processes news articles and predicts their authenticity (real or fake). This repository includes a trained model, preprocessing pipeline, and a simple Flask app for web-based analysis.

## Project Overview

This project utilizes Natural Language Processing (NLP) techniques to detect fake news in articles. Using a machine learning model, the system can predict whether a news article is real or fake based on its text. The model is trained on a dataset of labeled news articles and serves as a tool for analyzing news URLs via a Flask web app.

## Technologies Used

- Python
- Flask
- Scikit-learn
- nltk (Natural Language Toolkit)
- Pickle for model serialization
- Newspaper3k for article scraping

## Features

- **Web Interface**: Allows users to input a news article URL, automatically fetches the article content, and analyzes its authenticity.
- **Model**: A trained machine learning model to classify news articles as either fake or real.
- **Flask API**: A lightweight Python web framework that powers the prediction API.

## Installation

### Clone the Repository
```bash
git clone https://github.com/chaimaaskri/NLP_fake-news-analysis11.git
cd NLP_fake-news-analysis11
