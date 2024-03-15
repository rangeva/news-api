# Webz.io Free News API Lite Guide

## Getting Started in 3 easy steps
You only need to complete three steps to use the News API Lite.

### 1. Request an API Key

- Go to the [News API web page](https://webz.io/products/news-api#lite).
- Enter your email to receive your API key.

### 2. Make an API Request
Use the API key provided to make your first call to the API. Make sure you also specify a search term in the request. For example, the following API request will return news articles related to the search term “Bitcoin.” The default time frame is 3 days, but you can set this to up to 30 days.

- `https://api.webz.io/newsApiLite?token=[token]&q=Bitcoin`.

Here is a screenshot showing a part of the API call results in a web browser:

## 3. Explore Webz.io news data
Experiment with different API call configurations, refining your searches with advanced features like [filters and Boolean queries](https://docs.webz.io/reference/news-blogs-discussions-api-overview). For example, you could search for news articles about U.S. President Joe Biden or his presidential challenger Donald Trump, refining the search to return articles with negative sentiment:

`https://api.webz.io/newsApiLite?token=[token]&ts=0&q=title%3A(Trump%20OR%20Biden)%20sentiment%3Anegative`

This query includes negative news posts about President Biden or Donald Trump in the past 30 days. Here is a screenshot of the call results in a web browser:


## Limitations

- Up to 1,000 calls per month.
- Returns 10 articles per call.


