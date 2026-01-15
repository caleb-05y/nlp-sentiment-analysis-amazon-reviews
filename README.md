# Sentiment Analysis of Amazon Product Reviews

**NLP Capstone Project – ASU Online Data Science Bootcamp**  
Author: Caleb Nicholas Youhanna

## Overview
This project applies Natural Language Processing (NLP) techniques to analyze
customer sentiment in Amazon product reviews. The goal is to classify reviews
as **Positive**, **Negative**, or **Neutral** and explore semantic similarity
between customer feedback.

## Dataset
- **Source:** Datafiniti Amazon Consumer Reviews
- **Size:** 28,332 cleaned reviews
- **Text Field Used:** `reviews.text`

## Approach
- Cleaned and preprocessed raw review text
- Implemented sentiment analysis using **spaCy** with **TextBlob**
- Classified sentiment based on polarity scores
- Measured semantic similarity between reviews using word embeddings

## Tools & Technologies
- Python
- pandas
- spaCy (`en_core_web_md`)
- spacy-textblob
- NLP preprocessing & sentiment polarity analysis

## Results
- Successfully classified sentiment across 28K+ reviews
- Demonstrated accurate polarity detection for positive and negative feedback
- Achieved high semantic similarity scores between related reviews

## Example Output
Polarity: 0.80 | Sentiment: Positive
Polarity: -0.45 | Sentiment: Negative

## Key Skills Demonstrated
- Natural Language Processing (NLP)
- Text preprocessing & cleaning
- Sentiment analysis
- Semantic similarity using embeddings
- Working with real-world, noisy datasets

## How to Run
1. Install dependencies:
pip install -r requirements.txt
2. Download a compatible Amazon reviews dataset from Datafiniti
3. Run the notebook `sentiment_analysis.ipynb`
