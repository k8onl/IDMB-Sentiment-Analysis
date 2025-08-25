Sentiment Analysis on IMDb Movie Reviews

Description

This project realizes a sentiment analysis pipeline for IMDb movie reviews to predict whether they are positive or negative. The notebook carries out exhaustive text preprocessing, exploratory data analysis (EDA), and model training with machine learning. It also has functionality to predict the sentiment of new user-input reviews.

Key Features:





Data Loading: Loads the IMDb dataset using Pandas.



Exploratory Data Analysis (EDA): Examines dataset composition, sentiment distribution, and statistics of review length using visualizations (histograms, boxplots, and bar charts).



Text Preprocessing: Preprocesses text by lowercasing, removal of HTML tags, punctuation removal, number removal, stopword removal, and lemmatization with NLTK.



Visualization: Displays the most frequently used words in positive and negative reviews.



Feature Extraction: Transforms text into numerical form with TF-IDF vectorization, optimized against review length statistics (mean=1309, min=32, max=13704, median=970).



Model Training: Trains and compares the accuracy of two classifiers—Logistic Regression and Naive Bayes—using Scikit-learn.



Prediction: Accepts a new review from the user and predicts its sentiment based on both trained models.

Tools Used:





Python Libraries: Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn



Dataset: IMDb Movie Reviews dataset

How to Use:





Clone the repository.



Install required dependencies: pip install pandas nltk scikit-learn matplotlib seaborn.



Download NLTK resources: nltk.download(['punkt', 'punkt_tab', 'stopwords', 'wordnet']).



Execute the Jupyter notebook (sentiment_analysis.ipynb) to run the analysis and try out new reviews.

Author:





Name: Omar Atef Ahmed



Task: First Task - Sentiment Analysis on IMDb Movie Reviews



GitHub: https://github.com/k8onl



LinkedIn: https://www.linkedin.com/in/k8onl

This is my first task with Elevvo Pathways, showcasing skills in natural language processing, data analysis, and machine learning. Suggestions and contributions are welcome!
