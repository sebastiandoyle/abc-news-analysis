# ABC News Analysis

NLP-powered analysis of ABC News articles. Scrapes articles, runs sentiment analysis and topic clustering, and outputs interactive HTML visualizations showing media coverage patterns over time.

## Features

- **Article scraping** from ABC News RSS feeds
- **Sentiment analysis** — positive/negative/neutral scoring per article
- **Topic clustering** — automatic grouping of related stories using TF-IDF
- **Temporal trends** — how sentiment and topic distribution shift over time
- **Interactive HTML output** — self-contained visualization you can open in any browser
- **Export to CSV** for further analysis

## Tech Stack

- Python 3
- NLTK / TextBlob (sentiment)
- scikit-learn (TF-IDF, clustering)
- BeautifulSoup (scraping)
- Plotly (interactive charts)
- Pandas

## Getting Started

```bash
git clone https://github.com/sebastiandoyle/abc-news-analysis.git
cd abc-news-analysis
pip install -r requirements.txt
python analyze.py
```

Output HTML files are generated in the `output/` directory.

## Sample Insights

The analysis reveals patterns like topic clustering around election cycles, sentiment shifts during crisis events, and the relative balance of positive vs. negative framing across different news categories.

## License

MIT
