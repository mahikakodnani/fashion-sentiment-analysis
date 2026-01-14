# Fashion Sentiment Analysis: E-Commerce Customer Insights
Automated sentiment analysis of e-commerce fashion reviews using a custom Machine Learning pipeline.

## Project Overview
As an MBA Tech student at NMIMS, I developed this project to demonstrate how Natural Language Processing (NLP) can be used to transform thousands of unstructured customer reviews into actionable business intelligence. 
By automating sentiment detection, brands can identify product flaws, improve customer satisfaction, and optimize supply chain decisions in real-time.

## The Technical Pipeline
I built a custom machine learning workflow using Python to process and classify 23,000+ fashion reviews:

Data Preprocessing: Cleaned text data using Regex to remove noise and standardized it for analysis.

Feature Extraction: Implemented TF-IDF Vectorization with Unigrams and Bigrams to capture the context of customer feedback (e.g., distinguishing "good" from "not good").

Model Selection: Utilized Logistic Regression for its high performance and business interpretability.

Evaluation: Achieved a 92.7% Accuracy score, verified through a Confusion Matrix to ensure reliability.

## Key Business Insights
Pain Point Discovery: The AI automatically flagged "fabric quality" and "sizing inconsistency" as the primary drivers for negative reviews.

Strategic Impact: Using this tool, a brand can reduce manual time by over 90%, allowing marketing teams to focus on strategy rather than data entry.

## Getting Started
Clone the Repo: git clone https://github.com/mahikakodnani/fashion-sentiment-analysis.git.

Install Dependencies: pip install -r requirements.txt.

Run the Analysis: Open fashion_sentiment_analysis (1).ipynb in Jupyter Notebook.

## Confusion matrix 
<img width="596" height="414" alt="image" src="https://github.com/user-attachments/assets/0c7073a6-ad87-41d9-b17d-c6a1ec40418d" />
