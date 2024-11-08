
# Sentiment Analysis Using Random Forest Classifier

## Goal
The goal of this project is to create a simple sentiment analyzer for IMDB movie reviews using a Random Forest Classifier.

## Methodology

### 1. Data Collection
The data for this project was collected from Kaggle and is also uploaded in this repository. The dataset consists of movie reviews from IMDB, labeled with sentiment classes (positive or negative).

### 2. Data Preprocessing
- **Tokenization:** The text data was tokenized to break it into individual words.
- **Stop Words Removal:** Common stop words (e.g., "the", "and", "is") were removed to focus on meaningful words.
- **Stemming:** Words were reduced to their root forms (e.g., "running" -> "run").

### 3. Text Vectorization
The processed text data was converted into a numerical form using **TF-IDF Vectorizer**. This method transforms the text into a matrix of features, where each feature represents the importance of a word in the document relative to the entire corpus.

### 4. Model Training and Prediction
A **Random Forest Classifier** was used to train the model on the preprocessed text data. The classifier was then used to predict sentiment labels (positive or negative) for unseen reviews.

### 5. Evaluation Metrics
The model was evaluated using the following metrics:
- **Precision:** Measures the accuracy of positive predictions.
- **Recall:** Measures how many actual positives were correctly identified.
- **F1-Score:** The harmonic mean of precision and recall.
- **Accuracy:** The overall accuracy of the model.

## Conclusion
This sentiment analysis model uses Random Forest Classifier and standard text preprocessing techniques to classify IMDB movie reviews into positive or negative sentiment categories.
