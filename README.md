# RAI.AI – Customer Review Intelligence Platform

## Overview
RAI.AI is an AI-powered platform for analyzing customer reviews using sentiment analysis and Large Language Models (LLMs). The system classifies customer feedback, extracts insights, and generates actionable business recommendations to help organizations better understand customer opinions at scale.

---

## Key Features

### Data Preprocessing & Cleaning
- Cleaned and standardized Arabic text data before analysis
- Removed numbers, URLs, hashtags, English characters, and special symbols
- Applied Arabic text normalization to improve consistency and model performance
- Prepared high-quality dataset to ensure reliable sentiment classification

### Sentiment Analysis
- Uses a CAMeL-BERT model trained on **100K labeled review samples** with 74% accuracy
- Classifies customer reviews into sentiment categories (positive , negative , mixed)
- Detects patterns and trends in customer feedback

### AI-Powered Insights
- Leverages Large Language Models (LLMs) to generate summaries and recommendations
- Identifies recurring issues and business opportunities from reviews

### Data Visualization
- Interactive visualizations including bar charts and heatmaps
- Helps in understanding sentiment distribution and hidden patterns



---

## Data

- **Model Training Data:** CAMeL-BERT trained on 100K labeled review dataset  
- **Analysis Data:** Cleaned AURA dataset (only preprocessed and cleaned customer reviews were used)  
- Data preprocessing included removal of noise, duplicates, and irrelevant characters

---

## Tech Stack

- Python  
- CAMeL-BERT (NLP Sentiment Model)  
- Large Language Models (LLMs)  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Streamlit (if applicable)

---

## Workflow

1. Data Collection and Cleaning (AURA dataset)
2. Sentiment Classification using CAMeL-BERT
3. Insight Generation using LLMs
4. Data Visualization using charts and heatmaps


---
#Impact
- Converts raw customer feedback into structured insights
- Reduces manual effort in analyzing large volumes of reviews
- Helps organizations make faster, data-driven decisions
- Improves understanding of customer sentiment at scale
- Supports analysis of Arabic customer reviews across multiple dialects, improving accessibility for regional data

---

## Future Improvements

- Real-time review analysis pipeline for continuous feedback processing
- Enhanced support for Arabic dialects with improved sentiment accuracy
- Creation of more interactive and customizable dashboards
- Integration of an AI chatbot for querying insights and answering data related questions
- Automated data cleaning and preprocessing 
- Advanced recommendation engine using fine tuned LLMs
