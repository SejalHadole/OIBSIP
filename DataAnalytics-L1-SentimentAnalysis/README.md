# Twitter Text Classification — Oasis Infobyte Internship

## Project Overview
This project uses Natural Language Processing (NLP) and Machine Learning to classify tweets into two categories: non-racist/non-sexist and racist/sexist.

## Dataset
- Total records: 31,962 tweets
- Target column: `label`
- Class 0: Non-racist/non-sexist
- Class 1: Racist/sexist

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- TF-IDF Vectorization
- Logistic Regression

## Methodology
1. Loaded and explored the dataset.
2. Cleaned and preprocessed tweet text.
3. Split the data into training and testing sets.
4. Converted text into numerical features using TF-IDF.
5. Trained a Logistic Regression model.
6. Evaluated the model using accuracy, precision, recall, F1-score, and a confusion matrix.

## Results
- Test Accuracy: 93.35%
- Class 0 F1-score: 0.96
- Class 1 F1-score: 0.62

## Conclusion
The model successfully classified sample tweets. Performance was stronger for Class 0 than Class 1, so further improvements are needed for Class 1.

## Internship
Oasis Infobyte Data Analytics Internship — Task 4
