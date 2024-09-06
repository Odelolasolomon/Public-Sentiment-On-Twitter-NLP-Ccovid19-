# Public-Sentiment-On-Twitter-NLP-Ccovid19-
## COVID-19 Sentiment Analysis Using Twitter API

This project analyzes public sentiment regarding COVID-19 by fetching real-time tweets using the Twitter API and applying Natural Language Processing (NLP) techniques to classify the sentiments of the tweets (positive, negative, neutral).

## Features

- **Twitter API Integration:** Fetches live tweets related to COVID-19.
- **NLP with NLTK:** Preprocesses tweets and classifies sentiments using natural language processing.
- **Sentiment Classification:** Identifies and categorizes tweets as positive, negative, or neutral.
- **Data Visualization:** Visualizes sentiment distribution through various charts.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/your-username/covid19-sentiment-analysis.git
cd covid19-sentiment-analysis
pip install -r requirements.txt
```
## Requirements
- Python 3.7+
- Tweepy (for Twitter API access)
- NLTK (for Natural Language Processing)
- Matplotlib, Seaborn (for visualization

## Twitter API Setup
- Create a Twitter Developer account.
- Generate your API keys (API key, API secret key, Access token, Access token secret).
- Create a .env file in the root directory and add your keys:

## TWITTER_API_KEY=your_api_key
- TWITTER_API_SECRET_KEY=your_secret_key
- TWITTER_ACCESS_TOKEN=your_access_token
- TWITTER_ACCESS_TOKEN_SECRET=your_access_token_secret

## Data Visualization
The sentiment analysis results is visualized using charts, showing the distribution of positive, negative, and neutral sentiments.

## Contributing
- Contributions are welcome! To contribute:

- Fork the repository.
- Create a new branch: git checkout -b feature/YourFeature
- Commit your changes: git commit -m 'Add your feature'
- Push to the branch: git push origin feature/YourFeature
- Open a pull request.

