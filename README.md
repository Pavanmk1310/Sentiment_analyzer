This program leverages the Hugging Face Transformer library to import a tokenizer and BERT model for performing sentiment analysis. The specific model utilized can be found here: BERT Multilingual Sentiment Analysis Model.

For the web scraping component, the program employs BeautifulSoup and Regex to efficiently extract comments from the review page. These extracted comments are then fed into the BERT model for sentiment analysis.

Additionally, the program utilizes Pandas to create a DataFrame that stores the model's output, ensuring organized and accessible data management.
