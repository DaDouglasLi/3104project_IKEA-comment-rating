# New Secondary Rating Prediction Project

## Quick Start

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy sentence-transformers vaderSentiment
```

### Running the Project

1. Open `submission/final_project_newsecrating.ipynb` in Jupyter Notebook
2. Ensure `submission/ikea_cleaned.csv` is in the submission folder
3. Run all cells sequentially

**Note**: The SBERT model (~80MB) will download automatically on first run.

## Files

- **`submission/final_project_newsecrating.ipynb`** - Main project notebook (run this)
- **`submission/ikea_cleaned.csv`** - Required dataset
- **`submission/data cleaning.ipynb`** - Optional data preprocessing
- **`submission/scrape_many_at_a_time.ipynb`** - Optional web scraping script
