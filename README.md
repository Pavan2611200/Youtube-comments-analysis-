# Youtube-comments-analysis-

\\   📌 Project Overview

The Emotion Detector for YouTube Comments is a Natural Language Processing (NLP) based project that analyzes audience comments from YouTube videos and identifies the overall sentiment of viewers.

The system automatically extracts comments from a YouTube video, performs sentiment analysis using TextBlob, classifies emotions into different categories, generates a star rating, and visualizes the results using charts and graphs.

This project helps content creators understand audience reactions without manually reading thousands of comments.

🎯 Objectives
Extract comments from YouTube videos automatically.
Perform sentiment analysis using NLP techniques.
Classify comments into:
Good
Medium
Bad
Worst
Generate an overall star rating.
Visualize audience sentiment using charts.
Provide insights about audience opinions.
🛠️ Technologies Used
Technology	Purpose
Python	Core Programming
Google Colab	Development Platform
YouTube Data API v3	Comment Extraction
TextBlob	Sentiment Analysis
Pandas	Data Processing
Matplotlib	Data Visualization
⚙️ System Workflow
User enters a YouTube Video URL.
Extract Video ID from the URL.
Fetch comments using YouTube Data API v3.
Clean and preprocess comments.
Perform sentiment analysis using TextBlob.
Classify emotions into:
Good
Medium
Bad
Worst
Generate overall star rating.
Display results through charts and graphs.

📂 Main Modules
Module 1: Video URL Input

Accepts YouTube video URL from the user.

Module 2: Comment Extraction

Retrieves comments using YouTube Data API v3.

Module 3: Text Preprocessing

Cleans comments by removing unwanted characters, links, and symbols.

Module 4: Sentiment Analysis & Emotion Classification

Analyzes sentiment polarity using TextBlob and categorizes comments.

Module 5: Star Rating & Visualization

Generates an overall rating and visualizes sentiment distribution.

😊 Emotion Categories
Sentiment Score	Category
Very Positive	Good
Positive/Neutral	Medium
Negative	Bad
Highly Negative	Worst
⭐ Star Rating System

The project generates an overall rating based on average sentiment scores:

⭐⭐⭐⭐⭐ Excellent Audience Response
⭐⭐⭐⭐ Good Response
⭐⭐⭐ Average Response
⭐⭐ Poor Response
⭐ Very Poor Response
📊 Output Features
Automatic comment extraction
Sentiment analysis using TextBlob
Emotion classification
Overall star rating generation
Bar chart visualization
Pie chart visualization
Audience sentiment summary

✅ Advantages

Reduces manual effort.
Faster analysis of large comment datasets.
Helps creators understand audience reactions.
Provides visual insights.
Easy to use and scalable.
Supports data-driven decision making.

🚀 Future Enhancements

Integration of BERT and RoBERTa models.
Support for multilingual comments.
Real-time sentiment monitoring.
Emoji sentiment detection.
Sarcasm detection.
Interactive web dashboard.
Support for Instagram, Facebook, and X (Twitter).

📸 Sample Outputs

Input YouTube URL
Comment Analysis Results
Emotion Classification
Star Rating Generation
Bar Chart Visualization
Pie Chart Visualization

👨‍💻 Developed By
Student Project
Emotion Detector for YouTube Comments Using NLP and Sentiment Analysis
Developed as a mini project to explore Natural Language Processing (NLP), Sentiment Analysis, Data Visualization, and YouTube Data API integration.

🙏 Acknowledgement
We would like to thank our faculty members and institution for providing guidance and support throughout the development of this project.

⭐ If you found this project useful, please give it a star on GitHub! ⭐
