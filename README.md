Project: Text Classification Using SGDClassifier
This project is a text classification system that uses Stochastic Gradient Descent (SGDClassifier) to classify tweets as spam/toxic (1) or not (0).
It preprocesses text data, balances the dataset, converts text into numerical features using TF-IDF, and trains an SGD-based classifier for prediction.

Features:
✔ Text preprocessing – Cleans text by removing special characters, links, and mentions.
✔ Data balancing – Upsamples the minority class to prevent model bias.
✔ TF-IDF transformation – Converts text into numerical vectors.
✔ SGDClassifier-based model – Fast and scalable classification using Stochastic Gradient Descent.
✔ Evaluation metrics – Uses F1-score to measure performance.

Model Performance:
The model was evaluated using F1-score, which balances Precision and Recall.
Results may vary based on dataset size and preprocessing steps.

