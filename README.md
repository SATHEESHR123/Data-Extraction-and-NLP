# Data-Extraction-and-NLP

web scraping and natural language processing (NLP) tasks. Here's a breakdown of the key steps and skills demonstrated in the notebook:

Web Scraping:

Using BeautifulSoup to scrape webpage content (titles, paragraphs) from URLs.
Handling HTTP requests with requests library and customizing headers to avoid blocking.
Saving scraped data into text files.
Text Preprocessing:

Using nltk (Natural Language Toolkit) for tokenizing text and removing stopwords.
Using regex to clean text (e.g., removing non-alphanumeric characters and punctuation).
Filtering tokens based on stop words and syllable count.
Sentiment Analysis:

Loading predefined positive and negative words and analyzing sentiment based on the occurrence of these words in the text.
Calculating polarity score and subjectivity score based on sentiment analysis.
Text Metrics:

Computing various readability metrics such as average sentence length, percentage of complex words, and Fog Index.
Measuring syllable count and identifying complex words (words with more than two syllables).
Calculating word count and average word length after removing stopwords and punctuation.
Pronoun Counting:

Using regex to count personal pronouns (e.g., "I", "we", "my", etc.) in the text.
Data Handling:

Reading data from Excel files with pandas.
Storing the processed results into a DataFrame and saving the final output into a CSV file.
These tasks are relevant to NLP, sentiment analysis, and web scraping. The code integrates multiple skills such as:

Python programming
Text data extraction and cleaning
Sentiment analysis using predefined lexicons
Use of libraries like BeautifulSoup, requests, nltk, and pandas
