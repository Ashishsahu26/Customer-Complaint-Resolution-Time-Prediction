# Customer-Complaint-Resolution-Time-Prediction

This project aims to predict the expected resolution time (in hours) for customer complaints using Natural Language Processing (NLP) and Machine Learning Regression techniques.

Customer complaints, usually written in free text form, contain valuable information about the issue type and its severity.
By analyzing the text (complaint narrative), the model predicts how long it might take to resolve similar issues in the future — helping organizations prioritize and allocate resources efficiently.

The steps involves:

1. Data Preprocessing & Cleaning:

Removal of special characters, numbers, and stopwords using Regular Expressions (regex) and NLTK.

Conversion of text to lowercase and cleaning for uniformity.

2. Feature Extraction:

Conversion of cleaned text into numerical format using TF-IDF Vectorization, which captures the importance of words in the complaint text.

3. Model Training (Regression):

A Linear Regression model was trained to learn the relationship between complaint text patterns and their corresponding resolution times.

Evaluation:

The model’s performance was measured using Mean Absolute Error (MAE) and R² Score to evaluate prediction accuracy.

4. User Interaction (Bonus):

Added a feature allowing users to input their own complaint text and get an estimated resolution time instantly
