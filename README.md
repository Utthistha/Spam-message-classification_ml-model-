**Project Overview**
• Created a machine learning model that detects/classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing.
• Engineered features like word_count, contains_currency_symbol, and contains_number from the text SMS.

How will this project help?
• This project helps in filtering/cleaning the SMS from the phone.

**Exploratory Data Analysis (EDA)**
• Exploring NaN values in dataset
• Plotted countplot for SMS labels Spam vs. Ham

**Feature Engineering**
• Handling imbalanced dataset using Oversampling
• Creating new features from existing features e.g. word_count, contains_currency_symbol, contains_numbers, etc.

**Data Cleaning**
Model Building and Evaluation
Metric: F1-Score
• Multinomial Naive Bayes: 0.943
• Decision Tree: 0.98
• Random Forest: 0.994
• Voting (Decision Tree + Multinomial Naive Bayes): 0.98
