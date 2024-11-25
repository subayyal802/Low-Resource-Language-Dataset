# Breaking Language Barriers: Dataset Development for Low Resource Language

This repository contains the dataset and code files for the project *Breaking Language Barriers: Dataset Development for Low Resource Language*. It aims to support Natural Language Processing (NLP) research for low-resource languages by providing structured datasets and preprocessing tools.

## Dataset Details
- File formats: CSV, JSON.
- Languages included: Urdu
- url used: [https://www.bbc.com/urdu]


## Repository Contents

### Code Files (`.ipynb`)
- **Scraping Code**: Code to scrape articles, topics, and summaries from the target website.
- **Preprocessing and Truncation Code**: Scripts for cleaning, truncating, and organizing the dataset into usable formats.

### Dataset Files
#### **JSONL Files**:
- `Articles`: Original articles scraped from the website.
- `Topics`: Topics associated with the articles.
- `Summary`: Summaries corresponding to the articles.
- `Articles-test`: Test set for articles.
- `Articles-train`: Training set for articles.
- `BBCArticle512` and `BBCArticle512J`: Preprocessed articles capped at 512 tokens.
- `BBCArticle512-test` and `BBCArticle512-train`: Train and test splits for preprocessed articles.
- `Length-Article-512`: Tokenized article lengths (512 tokens).
- `Length-Article-initial`: Initial token lengths for raw articles.

#### **Text Files**:
- `Length-Summary-512`: Token lengths of preprocessed summaries (512 tokens).
- `Length-Summary-Initial`: Token lengths of raw summaries.
- `Len-TestArticle-512`: Token lengths for test articles (512 tokens).
- `Len-TestSummary-512`: Token lengths for test summaries (512 tokens).
- `Log`: Log file of preprocessing steps.
- `Ratios-512`: Length ratios of articles to summaries (512 tokens).
- `Ratios-Initial`: Initial length ratios of articles to summaries.
- `TestRatio-512`: Length ratios for the test set (512 tokens).


## How to Use

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/subayyal802/Low-Resource-Language-Dataset

