# Hate-Speech-Detection
Built a model predicting 'hate' in the specific text. This can be useful to detect inappropriate comments on Social Media platforms.
🔍 Project Highlights:
1) Data Lookup: Classified data into three categories:
 - 0: Hate speech
 - 1: Offensive language
 - 2: Neither hate nor offensive

2) Data Cleaning: Improved data quality by:
 - Removing unwanted characters from the text.
 - Eliminating stopwords.
 - Performing stemming (Snowball Stemming).

3) Data Visualisation: Gained insights with:
 - Countplot of categories (0, 1, 2)
 - Plotting word count distribution for each category

4) Model Building: Developed a robust model using:
 - Count Vectorizer and TF-IDF for feature extraction.
 - RandomForestClassifier for classification.

5) Model Evaluation: Achieved impressive results with:
 - Confusion matrix analysis.
 - Precision score of 88%.
