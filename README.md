# Stock Market Commentary Analysis Notebook
This Jupyter Notebook is designed to perform an analysis of stock market commentaries related to the NASDAQ-AAPL stock on TradingView. The notebook utilizes Python libraries such as pandas, BeautifulSoup, Transformers, yfinance, seaborn, and matplotlib to gather, preprocess, analyze, and visualize data.

## Table of Contents

1. Data Scraping
Scraping Trading Ideas from TradingView
2. Data Preprocessing
Cleaning and Structuring Scraped Data
Adjusting Article Dates for Business Days
3. Sentiment Analysis
Utilizing the FinBERT Model for Sentiment Analysis
4. Visualizing Sentiment Distribution
Creating Histograms of Sentiment Scores
5. Stock Performance Analysis
Fetching Historical Stock Data using yfinance
Analyzing Future Stock Performance Following Commentary
6. Merging and Filtering Data
Merging Commentary and Stock Data
Filtering Data for Authors with Positions and Return Data
7. Conclusion
Slight Positive Correlation Between Position and Sentiment
Analyzing Future Stock Performance Following Commentary
## Purpose
The notebook aims to provide insights into the relationship between stock market commentary sentiment, the positions taken by authors, and the subsequent stock performance. It fetches and analyzes commentaries from TradingView, performs sentiment analysis on the commentaries using the FinBERT model, and explores the stock's performance following the commentaries.

## Usage 
Installation: Before running the notebook, ensure you have the required Python libraries installed. You can install them using the following command:
pip install pandas beautifulsoup4 transformers yfinance seaborn matplotlib

Execution: Run each cell in the notebook sequentially. The notebook contains markdown comments and code blocks guiding you through each section of the analysis.

Configuration: Adjust parameters such as the number of pages to scrape, the sentiment analysis model, and the stock ticker symbol to tailor the analysis to your requirements.

Output: Throughout the notebook, you'll find various visualizations, including sentiment score histograms and stock performance analyses.
Results
The notebook generates visualizations that illustrate the sentiment distribution of commentaries, allowing you to observe trends in sentiment over time. Additionally, it analyzes the stock's performance following authors' commentaries with positions, shedding light on potential correlations between sentiment, positions, and stock movement.

## Acknowledgments
This notebook utilizes the FinBERT model from Hugging Face's Transformers library for sentiment analysis.
Historical stock data is obtained using the yfinance library.
TradingView is the source of the stock market commentaries.
## Note
The information provided in this notebook is for educational and analytical purposes only. It does not constitute financial advice, and any investment decisions should be based on thorough research and consultation with financial experts.

Happy analyzing and learning from the world of stock market commentary!
