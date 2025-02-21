# Sentimental Analysis Chatbot
## Overview
This project implements a sentiment analysis chatbot using Flask, NLTK for text preprocessing, and a Logistic Regression model for sentiment classification. Users interact with the chatbot through a web interface where they can input messages related to movies, and the chatbot predicts whether the sentiment of the message is positive, negative, or neutral based on an IMDB dataset-trained Logistic Regression model.
## Features
- **User Interface:** Simple web interface for users to input messages.
- **Sentiment Analysis:** Predicts sentiment (positive, negative, neutral) of user messages.
- **Clear Functionality:** Provides a clear button to reset the input message and response.
## Set Up Instructions
### Prerequisites
- Python (3.6+ recommended)
- pip (Python package installer)
### Installation
1. Clone the repository
```bash
git clone https://github.com/Jahnavi-57/Chatbot-with-Sentimental-Analysis.git
cd Chatbot-with-Sentimental-Analysis
```
2. Install dependencies:
```bash
pip install flask nltk scikit-learn pandas
```
3. Download NLTK resources:
```bash
python -c "import nltk; nltk.download('stopwords')"
```
### Running the Application
1. Navigate to the project directory:

```bash
cd Chatbot-with-Sentimental-Analysis
```
2. Run the Flask application:
```bash
python app.py
```
3. Access the application:
Open a web browser and go to http://localhost:5000 to use the chatbot.
## Usage
- Enter a message related to movies in the input box.
- Click "Send" to see the predicted sentiment (positive, negative, neutral).
- Click "Clear" to reset the input message and response.
## Dependencies
- Flask: Web framework for Python.
- NLTK: Natural Language Toolkit for text preprocessing.
- scikit-learn: Machine learning library for logistic regression and vectorization.
- pandas: Data manipulation and analysis library.
## Project Structure
```graphql
project-root/
│
├── app.py                    # Flask application setup and routes
├── templates/                # HTML templates for web interface
│   ├── main.html            # Main template for chatbot interface
├── static/                   # Static files (CSS, images)
│   ├── main.css              # Stylesheet for HTML templates
│   ├── chatbot.png           # Image file for the chatbot
├── IMDB_Dataset.csv          # Dataset for sentiment analysis (IMDB reviews)
├── README.md                 # Project README file (this file)
└── requirements.txt          # List of Python dependencies (optional)

```
## Screenshot
![Screenshot 2024-06-29 231250](https://github.com/Jahnavi-57/Chatbot-with-Sentimental-Analysis/assets/130915370/bb0289d2-fbb5-478f-b6ab-e43c68a07edf)

