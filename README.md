## NLP YouTube Comments Scraper
This project uses the YouTube Data API v3 to scrape comments from a specific YouTube video, storing them in a structured format for further Natural Language Processing (NLP) tasks or data analysis.

## Features
Connects to YouTube using Google's official API client.

Fetches up to 100 comment threads per request.

Stores comments in a pandas DataFrame for easy processing.

Ready for further NLP or sentiment analysis work.

##      Section           |             Description
1. Setup                  | Install packages, set up the YouTube API
2. API Request            | Connect to YouTube and retrieve comments
3. Data Processing        | Store results in DataFrame, clean data
4. NLP Preprocessing      | Tokenization, stop word removal, stemming
5. Visualization          | Word cloud, frequency distribution

## Output

Top Words: Extract the most used terms across comments

Word Clouds: Get a visual overview of comment themes

Comment Volume: Explore trends in comment activity

## Limitations

1.YouTube API quota is limited; frequent or large-scale scraping may hit limits.

2.Only fetches top-level comments (not replies by default).

