# News_sentiment_correlation_project

## Introduction

Welcome to the Financial News Sentiment Analyzer! This tool is designed to help users gauge the impact of news sentiment on financial markets. By aggregating and analyzing news articles, it highlights how sentiments expressed in financial news can correlate with market movements, providing insights that can guide investment decisions.

## Project Overview

Our application simplifies the analysis of financial news impact on markets. Traditionally, understanding this impact involved manually reading numerous articles, summarizing them, and then correlating their sentiment with market trends—often a very time-consuming task. This project automates these processes through advanced natural language processing (NLP) and sentiment analysis techniques.

## How It Works

1. **Web Scraping**: Utilizes Python scripts to scrape financial news from websites like Bloomberg, Reuters, and WSJ.
2. **Article Summarization**: Employs NLP libraries to extract key information from articles, streamlining the data for easier processing.
3. **Sentiment Analysis**: Analyzes the sentiment of each article using the VADER algorithm, classifying sentiments into positive, negative, or neutral categories based on both the headline and the content.
4. **Data Visualization**: Visualizes sentiment scores alongside financial market data, presenting trends and correlations through an interactive dashboard.
5. **User Interaction**: Through a web interface, users can select specific news sources and financial assets to tailor the analysis to their needs.

## Installation Instructions

Set up this tool on your local system by following these steps:

1. Clone the project repository from GitHub: [https://github.com/shreyashguptas/News_sentiment_correlation_project](https://github.com/shreyashguptas/News_sentiment_correlation_project)
2. Ensure Python 3.8 or later is installed on your system.
3. Install required Python packages: `pip install os pandas numpy dateutil vaderSentiment matplotlib`
4. Launch the application: `python app.py`
5. Access the web interface via your browser here.

## Required Python Packages

- `os`: For operating system dependent functionality.
- `pandas`: For data manipulation and analysis.
- `numpy`: For support with large, multi-dimensional arrays and matrices.
- `dateutil`: For parsing dates.
- `vaderSentiment`: For sentiment analysis.
- `matplotlib`: For creating static, interactive, and animated visualizations in Python.

## Potential Pitfalls & Challenges

- **Web Scraping Fragility**: Changes in the layout of news websites can disrupt the scraping functions, necessitating regular updates to the code.
- **Sentiment Analysis Accuracy**: Financial jargon can complicate the accuracy of sentiment classification.
- **Resource Intensity**: The process of handling and analyzing large data sets can be computationally demanding.

## Future Directions

Enhance the accuracy of sentiment analysis with advanced NLP models. Broaden the scope to include analysis of earnings call transcripts or regulatory filings. Consider developing this tool into a commercial product for investment firms.

## How to Contribute

Contributions to the project are welcome! You can help by improving functionality, refining the user interface, or fixing bugs. Check our contribution guidelines for more details on how to submit pull requests.

## License

This project is freely available under the MIT License, permitting broad use and modification.

## Contact

For further information, please reach out to any of the project contributors:

- Tandem Young
- Jacob Meaders
- Shreyash Gupta

## Group Members

- Tandem Young
- Jacob Meaders
- Shreyash Gupta