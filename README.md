Overview
This project predicts an improved secondary rating (NewSecRating) for IKEA product reviews using sentiment analysis and topic clustering.
Files in Submission Folder
scrape_many_at_a_time.ipynb - Web scraping script (optional, data already provided)
data cleaning.ipynb - Data preprocessing notebook (optional, cleaned data provided)
ikea_cleaned.csv - Cleaned dataset (required)
final_project_newsecrating.ipynb - Main project notebook (run this)
Quick Start
Prerequisites
Install required Python packages:
pip install pandas numpy matplotlib seaborn scikit-learn scipy sentence-transformers vaderSentiment
Or install individually:
pandas - Data manipulation
numpy - Numerical operations
matplotlib & seaborn - Visualization
scikit-learn - Machine learning (KMeans, LinearRegression, PCA, etc.)
scipy - Statistical functions
sentence-transformers - SBERT embeddings (will download model automatically)
vaderSentiment - Sentiment analysis
Running the Main Notebook
Open final_project_newsecrating.ipynb in Jupyter Notebook or JupyterLab
Ensure ikea_cleaned.csv is in the same directory
Run all cells sequentially (Cell → Run All)
The notebook will automatically install vaderSentiment if needed
SBERT model (all-MiniLM-L6-v2) will download automatically on first run (~80MB)
