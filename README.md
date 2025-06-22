# SENTIMENT-ANALYSIS

**COMPANY** : CODETECH IT SOLUTIONS

**NAME** : SHAIK SHAFIYA

**INTERN ID** : CT06DF1367

**DOMAIN** : DATA ANALYTICS

**DURATION** : 6 WEEKS

**MENTOR** : NEELA SANTHOSH KUMAR

# Sentiment Analysis on User Reviews Using NLP and Logistic Regression

### Project Description

This project demonstrates the implementation of a basic Natural Language Processing (NLP) pipeline for sentiment analysis on a large set of user-generated text data. The model classifies the sentiment of reviews into three categories: Positive, Negative, and Neutral. The analysis uses preprocessing, feature extraction, machine learning, and visualizations to deliver insights and evaluate model performance.

### Objective

The primary objective of this project is to:

- **Clean and preprocess raw textual data using NLP techniques**

- **Convert text into numerical vectors using TF-IDF**

- **Train a machine learning classifier (Logistic Regression)**

- **Predict sentiment labels for unseen text data**

- **Evaluate and visualize the model’s performance**

### Dataset Details

- **Name: sentiment_large_data.csv**

- **Format: CSV (Comma-Separated Values)**

- **Columns Used:**

   - **text: Raw user-generated text (e.g., reviews, tweets, etc.)**

   - **sentiment: Labeled sentiment (Positive, Negative, Neutral)**

- **Nature of Data: This is a generic sentiment classification dataset and not specific to any one domain like airlines or products.**

### Tools & Technologies Used

- **Python – Programming language**

- **Pandas – Data manipulation and preprocessing**

- **NLTK – Natural Language Toolkit for stopword removal and lemmatization**

- **Scikit-learn – For machine learning model building and evaluation**

- **Matplotlib & Seaborn – For data visualization and plotting**

  ### Methodology

  1. **Text Preprocessing:**

       - **Lowercasing and punctuation removal.**

       - **Stopword removal using NLTK.**

       - **Lemmatization for reducing words to their base form.**
    
  2. **Feature Extraction:**

        - **TF-IDF Vectorizer is used to convert clean text into numeric vectors.**
    
  3. **Model Training:**

        - **A Logistic Regression model is trained using the TF-IDF vectors and sentiment labels.**
    
  4. **Evaluation Metrics:**

        - **Classification Report (Precision, Recall, F1-score)**

        - **Accuracy Score**

        - **Confusion Matrix Heatmap**
    
  5. **Visualization:**
 
        - **Two side-by-side bar plots showing comparison between Actual and Predicted sentiment distributions, using consistent colors for each class (positive, neutral, negative).**

### Conclusion

This project presents a complete and lightweight pipeline for sentiment analysis using traditional NLP and machine learning techniques. The use of Logistic Regression along with TF-IDF provides a quick yet effective baseline for understanding sentiment in text.


### Output Highlights

  - **A detailed classification report with accuracy printed in the console.**

  - **A confusion matrix heatmap shows how well the model performs across sentiment classes.**

  ![Image](https://github.com/user-attachments/assets/fdfc7542-864b-44d0-a9e6-ec4a9cfa8ffb)

  
   - **Side-by-side bar plots:**

      - **Left: Original sentiment label distribution.**

      - **Right: Model’s predicted sentiment distribution.**

      - **Each sentiment is color-coded consistently to easily compare differences.**

   ![Image](https://github.com/user-attachments/assets/8848d8df-ba64-4a6e-be25-6efece0bfa37)







