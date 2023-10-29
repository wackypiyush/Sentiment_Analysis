# Sentiment Analysis and Readability Metrics

## Overview
This project performs sentiment analysis and calculates readability metrics for a collection of web articles. It extracts data from a given URL list, cleans and processes the text, and computes various scores, including positive and negative sentiment, polarity, subjectivity, and readability indices.

## Key Features
1. **Sentiment Analysis:**
   - Compute positive and negative scores.
   - Calculate polarity and subjectivity scores.

2. **Readability Metrics:**
   - Determine average sentence length.
   - Evaluate the percentage of complex words.
   - Compute the Fog Index for text complexity.
   - Analyze average words per sentence, complex word count, word count, syllables per word, personal pronouns, and average word length.

3. **Data Processing and Visualization:**
   - Extract text data from web articles.
   - Tokenize, clean, and process the text.
   - Generate informative visualizations like WordCloud.

## Usage
1. **Data Extraction:**
   - Provide the URL list in the `input.xlsx` file.
   - Run the data extraction script to collect and save articles in the 'Articles' folder.

2. **Calculations and Analysis:**
   - Utilize the Jupyter notebook to execute sentiment analysis and readability calculations.
   - Obtain results in the 'Sentiment_Analysis_Results.xlsx' file.

3. **WordCloud Visualization:**
   - Use the `generate_wordcloud` function in the notebook to create WordCloud visuals for individual articles.


## Dependencies
- pandas
- numpy
- seaborn
- matplotlib
- requests
- beautifulsoup4
- nltk
- wordcloud

## Note
- Handle exceptions and errors by referring to the console outputs.
- Customize stopwords and dictionaries for more accurate sentiment analysis.

Feel free to explore and enhance this project for more comprehensive text analysis!
