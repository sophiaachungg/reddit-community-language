# reddit-community-language

This repository contains an analysis of community belonging in various subreddits by examining the use of neologisms/slang and the sentiment of posts. The project explores whether the use of unique linguistic patterns—similar to those seen in physical communities—serves as an indicator of belonging in online communities.

## Project Overview

Neologisms and slang usage are often considered markers of group belonging in physical communities. This project aims to explore whether a similar pattern holds true in online communities, specifically in subreddits. By performing lexical analysis of neologisms and sentiment analysis of posts, we aim to identify the potential relationship between language use and a sense of community.

## Repository Contents

This repository includes templates of scripts used in different stages of the analysis:

1. **Reddit Scraping Script**: A script using the Reddit API to scrape the top 1000 posts from a specific subreddit within a given time frame.
2. **Text Cleaning Script**: A script for cleaning the scraped text, including removal of punctuation, special characters, and other preprocessing steps.
3. **Text Preprocessing Script**: A script to preprocess the cleaned text, including tokenization, lemmatization, and removing stop words.
4. **Neologism Extraction Script**: A script that filters out words present in standard dictionaries, resulting in a dataframe of neologisms or slang words used in the subreddit.
5. **Sentiment Analysis Script**: A script for analyzing the sentiment of the posts in different subreddits.

## Key Questions Addressed

- Does the use of neologisms or slang in subreddits reflect a stronger sense of community among participants?
- How does the size and topic of a digital community contribute to the amount of slang used?
- How does the amount of slang used contribute to belonging in a digital community?
- What are the sentiment dynamics across different subreddits, and how do they relate to neologism usage?

## Getting Started

To get started with the repository, you will need:
- Python 3.8+
- Jupyter Notebook
- Dependencies listed in `requirements.txt`

### Running the Scripts

1. Clone this repository:
   ```bash
   git clone <repo-url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the scripts sequentially to analyze data from subreddits of interest

## Project Structure

- `01-subreddit-scraper-template.ipynb` - Script for scraping subreddit posts.
- `02-subreddit-tidier-template.ipynb` - Script for cleaning raw text.
- `03-subreddit-tpp-template.ipynb` - Script for preprocessing cleaned text.
- `04-subreddit-lexical-analysis-template.ipynb` - Script for identifying and extracting neologisms.
- `05-subreddit-sentiment-analysis-template.ipynb` - Script for sentiment analysis of posts.
- `data/` - Folder for storing scraped and cleaned data.
- `output/` - Folder for storing analysis results.

## Future Work

This project is an initial step toward understanding the role of language in fostering online community belonging. Future work may include:
- Extending analysis to more subreddits to identify differences across diverse topics.
- Applying more sophisticated natural language processing (NLP) techniques to understand contextual / semantic relationships.
- Expanding sentiment analysis to include multiple dimensions of emotion.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request if you would like to add to or improve the analysis.

## Contact

For any questions or suggestions, please feel free to contact me.

---

Feel free to adjust any sections to better fit your project's details or add anything specific you'd like to include!
