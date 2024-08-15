# Text Classification: Sentiment Analysis of Movie Reviews

### Introduction
- This project focuses on classifying movie reviews as either positive or negative using machine learning techniques.
- Given a dataset of labeled movie reviews, the goal is to build a model that can accurately predict the sentiment of new, unseen reviews. This type of text classification has applications in various fields, including recommendation systems, social media analysis, and customer feedback analysis.

### Goal
- The primary goal of this project is to develop a text classification model that can determine whether a movie review is positive or negative based on its content.

### Dataset
- The dataset consists of movie reviews labeled as either positive (pos) or negative (neg). It can be accessed here. The dataset includes thousands of reviews, each associated with a sentiment label.

### Steps Involved
1. Data Loading and Cleaning
- The dataset was loaded into a pandas DataFrame, and the initial exploration was conducted to check for missing values and blank strings. Any reviews with missing or blank content were removed to ensure data quality.

2. Exploratory Data Analysis (EDA)
- Using a CountVectorizer, the most frequent words in both positive and negative reviews were identified. This step provided insight into the common language used in reviews of different sentiments, which is crucial for understanding the data distribution.

3. Data Preprocessing
- The text data was split into training and testing sets using an 80-20 split. The reviews were treated as the feature set (X), and the sentiment labels as the target variable (y).

4. Model Training
- A machine learning pipeline was created, combining TfidfVectorizer for text vectorization and LinearSVC for classification. The pipeline was trained on the training data to learn the relationship between the reviews and their sentiments.

5. Model Evaluation
- The model was evaluated on the test data, achieving an accuracy of 83%. The classification report showed balanced precision, recall, and F1 scores for both positive and negative classes. A confusion matrix was also plotted to visualize the model's performance.

### Conclusion
***The text classification model successfully predicted the sentiment of movie reviews with an accuracy of 83%. This project demonstrates the effectiveness of combining text vectorization with a supervised learning model in sentiment analysis tasks.***

Future Work
Future enhancements could include experimenting with different classifiers, performing hyperparameter tuning, and expanding the dataset to include more diverse reviews. Additionally, applying deep learning models like recurrent neural networks (RNNs) or transformers could potentially improve the model's accuracy.
