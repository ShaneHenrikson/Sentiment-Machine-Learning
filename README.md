Objective/Goal: The aim was to create a model that can automatically determine the sentiment (positive or negative) of movie reviews. This helps in understanding audience reactions and improving movie recommendations.

Dataset: I used the IMDb dataset, which contains thousands of movie reviews labeled as positive or negative. This data is crucial for training our model to recognize patterns in the text.

Algorithms: I explored three different machine learning models:
-Random Forest
-Support Vector Machine (SVM)
-Logistic Regression

Building and Evaluating the Models:
Data Preprocessing: Converted text reviews into numerical data using techniques like Bag-of-Words and TF-IDF, which help the models understand the text.

Training: Fed the preprocessed data into the models and adjusted their parameters to minimize errors.

Evaluation: Tested the models on new data to see how well they performed. Key metrics included accuracy, precision, recall, and F1-score.

Analyzing the Results:
-Logistic Regression emerged as the best performer with an accuracy of 88.08% and an F1-score of 88.12%.
-SVM also performed well, showing it’s a strong choice for text classification.
-Random Forest was good but not as precise as the other two.

Key Takeaways:
TF-IDF was more effective than Bag-of-Words in capturing the sentiment of reviews.

Understanding where models made mistakes (like misinterpreting sarcasm) can help improve future models. Attempting deep-learning with models like BERT would crash my computer.

This project was a fun and frustrating learning experience, filled with thousands of errors, failed programming scripts, diving into hours of research, and building better workflows for the future.
