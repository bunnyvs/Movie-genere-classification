# Movie-genere-classification
This project is focused on building a machine learning model to classify movies into their respective genres based on metadata like title, overview, and more. Movie-Genere-classification/ ├── Movie Genre Classification.ipynb ├── tmdb_5000_movies.csv ├── tmdb_5000_credits.csv └── README.md Overview The goal is to predict the genre(s) of a movie using available data from the TMDB 5000 Movie Dataset. We perform text processing, feature engineering, and apply machine learning algorithms to create a genre classification system.

🛠️ Tech Stack Python 🐍

Pandas

NumPy

Scikit-Learn

Natural Language Processing (NLP)

Jupyter Notebook 📊 Dataset We use the TMDB 5000 Movie Dataset, which includes:

tmdb_5000_movies.csv — Information like title, overview, genres, etc.

tmdb_5000_credits.csv — Cast and crew details.

Dataset Source: Kaggle TMDB 5000 Movie Dataset

Key Features Data Cleaning and Preprocessing

Merging Datasets (Movies + Credits)

Text Vectorization (using Bag of Words / TF-IDF)

Multi-label Genre Classification

Model Building (using classification algorithms like Random Forest, Logistic Regression)

Evaluation using Accuracy, Precision, Recall, F1-Score

Model Building Process Data Preprocessing

Merge movie and credit data

Extract useful features (genres, keywords, overview, cast)

Clean and transform text

Feature Engineering

Create a combined "tags" feature

Vectorize text data

Model Training

Train different ML classifiers

Evaluation

Compare performance metrics

Select the best model Results Achieved good classification performance using Random Forest Classifier.

Improved predictions with feature engineering (combining keywords, overview, cast).

Model Accuracy Precision Recall F1-Score Logistic Regression 84% 0.82 0.80 0.81 Random Forest 88% 0.86 0.85 0.85 (Note: These are sample values. Please replace with your actual results.)
