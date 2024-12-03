# Sentiment Analysis Web App
This is a simple web application built with Streamlit, TextBlob, and Pandas that allows users to perform sentiment analysis on input text and CSV files. The app categorizes text as Positive, Negative, or Neutral based on its sentiment polarity score. Additionally, it provides a text-cleaning feature for preprocessing input text.
# Features
# Sentiment Analysis of Text:
Enter any text, and the app will analyze its sentiment.
The sentiment is categorized into Positive, Negative, or Neutral based on polarity scores.
# Text Cleaning:
Clean your input text to remove unwanted characters and formatting using the cleantext library.
# Sentiment Analysis of CSV Files:
Upload a CSV file containing a "text" column. The app will analyze the sentiment of each row and display the results in the form of a new column ("Sentiment").
It visualizes the sentiment distribution of the text data in the CSV using a bar chart.
# Technologies Used
Streamlit: For creating interactive web apps.
TextBlob: For performing sentiment analysis.
Pandas: For data handling and processing.
CleanText: For cleaning the input text.
Matplotlib: For plotting the sentiment distribution.
# How to Use
1. Sentiment Analysis of Text
Go to the "Analyze Text" section.
Enter the text you want to analyze in the input box.
Click on "Analyze" to see the sentiment (Positive, Negative, or Neutral) and the polarity score.
2. Text Cleaning
Go to the "Clean Text" section.
Enter the text you want to clean.
Click on "Clean Text" to see the cleaned version of your input.
3. Sentiment Analysis of CSV Files
Go to the "Analyze CSV" section.
Upload a CSV file that contains a "text" column.
The app will automatically analyze the sentiment for each row in the CSV file and display the sentiment in a new column.
A bar chart will show the distribution of sentiments (Positive, Negative, Neutral).
# Requirements
To run this app locally, you need to install the following Python libraries:
pip install streamlit textblob pandas cleantext matplotlib



# Project Structure
app.py: Main Python file where the Streamlit app is created and run.
requirements.txt: File containing the list of dependencies required for the app.
README.md: Documentation for the project.
About
This is a simple sentiment analysis app that provides users with an easy-to-use interface to analyze the sentiment of text data. Whether you're working with short text inputs or large datasets, this app can help you quickly assess the sentiment.

# Developer Information



Arooj shareef
