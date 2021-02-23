# Homework 12: NLP

### Resources
- [Crypto Sentiment Notebook](crypto_sentiment.ipynb)

### Running the notebook

To run the notebook, ensure that you have a `.env` file present with the following key: `NEWS_API_KEY`. This should be your News API key for your account.

### Notes

The notebook analyzes the news of the Bitcoin and Ethereum cryptocurrencies.

The word cloud for Bitcoin shows frequent mentions of the following words: bitcoin, cryptocurrency, digital, future, elon musk, tesla, twitter. The words, **bitcoin** and **cryptocurrency**, are expected. At the time I pulled the news from the API, Tesla had just announced its purchase of $1.5 billion in Bitcoin.

![Bitcoin word cloud](bitcoin.png)

The word cloud for Ethereum shows frequent mentions of the following words: bitcoin, ethereum, reuters, and dollar. The words, **bitcoin** and **ethereum**, are expected. Ethereum's price is usually correlated with Bitcoin's price. The high frequency of "reuters" is likely because Reuters writes numerous articles about Ethereum.

![Ethereum word cloud](eth.png)