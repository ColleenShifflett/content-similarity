# Page Similarity Analysis Using TF-IDF

This repository contains a small-scale demonstration of how to analyze textual similarity between web pages using TF-IDF vectorization and cosine similarity.

## Business Problem

Large websites often contain overlapping, redundant, or duplicated content. This presents challenges for SEO, user experience, and long-term content management. The objective of this project is to identify similar pages by analyzing the text content of each page, helping organizations determine where they can reduce or consolidate content.

This approach can be particularly useful during:
- Website redesigns or migrations
- SEO audits
- Content governance reviews

## Project Goal

The goal of this notebook is to demonstrate a lightweight content similarity analysis pipeline. Specifically, it:
- Uses natural language processing to clean and tokenize page content
- Applies TF-IDF to vectorize the text
- Calculates pairwise similarity between pages using cosine similarity
- Visualizes the results in a similarity matrix heatmap

This allows content strategists or digital teams to quickly identify clusters of similar pages that may be candidates for consolidation or refinement.

## About the Data

All data used in this notebook is publicly available. For demonstration purposes, only a small sample is analyzed. No proprietary or sensitive content is included.

## What's Inside

- `content_similarity_analysis.ipynb`: The complete, annotated Jupyter Notebook
- Sample dataset (`refund-search-urls.csv`) expected to be present in the same directory

## Next Steps

This framework could be scaled or adapted to:
- Use full website crawl data or CMS exports
- Integrate additional metadata (e.g., traffic, conversions, SEO scores)
- Automate the process as part of a regular content health check

## License

This project is intended for educational and portfolio purposes.

