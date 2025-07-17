# Fake Review Detection

## Overview
This project aims to detect fake reviews using natural language processing (NLP) techniques. The workflow includes data exploration, text preprocessing, and preparation for machine learning model development.

## Dataset
- **File:** `fake reviews dataset.csv`
- The dataset contains reviews with the following columns:
  - `category`: The category of the product/service reviewed
  - `rating`: The numerical rating given
  - `label`: Indicates whether the review is fake or genuine
  - `text_`: The review text

## Preprocessing Steps
- Removal of punctuation, stopwords, and digits
- Tokenization of text
- Lowercasing all text
- Stemming and lemmatization
- Saving the preprocessed data to `Preprocessed Fake Reviews Detection Dataset.csv`

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- nltk
- scikit-learn

Install requirements with:
```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn notebook
```

## How to Run
1. Open the notebook `Fake Reviews Detection Part-1.ipynb` in Jupyter Notebook.
2. Run all cells to perform data loading, exploration, and preprocessing.
3. The preprocessed dataset will be saved as `Preprocessed Fake Reviews Detection Dataset.csv`.

## Next Steps
- Add feature extraction and machine learning model training for fake review detection.
- Evaluate model performance and interpret results. 