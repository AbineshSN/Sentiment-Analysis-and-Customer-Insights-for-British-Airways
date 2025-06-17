# Sentiment-Analysis-and-Customer-Insights-for-British-Airways

# Overview
This project focuses on extracting actionable customer insights from British Airways review data using Natural Language Processing (NLP) and data analysis techniques. The workflow includes web scraping, text preprocessing, sentiment analysis, topic modeling, and visualization to assess customer satisfaction across various service dimensions such as crew, food, timeliness, and seating.


# Objectives

Collect and structure review data from public sources using web scraping
Clean and preprocess textual and numerical data for analysis
Apply NLP techniques to extract sentiment and thematic insights
Visualize review patterns by traveler type, cabin class, and rating
Identify key service factors influencing customer satisfaction


# Technologies Used

Programming Language: Python 3.8+
Libraries: Pandas, Matplotlib, Seaborn, WordCloud, NLTK or spaCy
NLP Techniques: Tokenization, Stopword Removal, Topic Modeling (LDA), Sentiment Mapping
Visualization: Histograms, Word Clouds, Box Plots, Scatter Plots
Notebook Environment: Jupyter Notebook
Web Scraping: BeautifulSoup or Selenium (if implemented externally)


# Key Components

Data Collection: Scraped review data from public airline review sites (notebook starts with processed CSV)
Data Preprocessing: Filtered by rating, normalized text, removed stopwords, and prepared features for analysis
Sentiment Analysis: Mapped ratings to sentiment classes and analyzed rating distributions
Topic Modeling: Extracted common themes (crew service, food quality, seat comfort, timeliness) using co-occurrence patterns
Visualizations: 
1. Word clouds highlighting frequent terms
2. Histograms and box plots of ratings by traveler type and cabin class
3. Scatter plots showing correlations between service ratings and overall sentiment


# Project Structure

british-airways-sentiment/
├── data/                      # Processed dataset CSV
├── notebooks/                 # Jupyter notebook with full workflow
├── outputs/                   # Word clouds and other visualizations
├── README.md                  # Project documentation


# Results

Majority of reviews showed positive sentiment, with ratings skewed toward 4 and 5 stars
Topic modeling identified service quality, efficiency, and premium experience as recurring positive themes
Visual segmentation showed that traveler type and cabin class impact perceptions of comfort and service
