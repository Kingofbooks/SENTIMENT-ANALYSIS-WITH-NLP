# SENTIMENT-ANALYSIS-WITH-NLP

COMPANY: CODTECH IT SOLUTIONS

NAME: ARYAN SHARMA

INTERN ID: CT08PBS

DOMAIN: MACHINE LEARNING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION: ML Internship Project -SENTIMENT-ANALYSIS-WITH-NLP

Internship Institution: CODTECH

Task:PERFORM SENTIMENT ANALYSIS ON A DATASET OF CUSTOMER REVIEWS USING TF-IDF VECTORIZATION AND LOGISTIC REGRESSION.

This project focuses on sentiment analysis of customer reviews from the dataset "Womens Clothing E-Commerce Reviews.csv". The goal is to classify reviews as positive or negative using TF-IDF Vectorization and Logistic Regression.
The dataset contains customer reviews with various attributes. Key columns used:
Review Text → The actual customer review.
Recommended IND → Binary label (1 = Recommended, 0 = Not Recommended).
Tools & Technologies Used:
Python → Main programming language.
Pandas → Data handling & preprocessing.
NLTK → Text processing (stopword removal, tokenization).
Scikit-Learn → Machine learning (TF-IDF & Logistic Regression).
Steps Followed
1) Data Preprocessing
Loaded the dataset using pandas.
Selected Review Text and Recommended IND columns.
Handled missing values by dropping empty reviews.
Converted the sentiment column (Recommended IND) to 0 (Negative) and 1 (Positive).
2) Text Cleaning & Processing
Used NLTK to remove stopwords, punctuation, and special characters.
Tokenized the text to extract meaningful words.
Converted all text to lowercase.
3) TF-IDF Vectorization
Transformed the cleaned text into numerical features using TF-IDF.
Limited to 5000 most important words for better performance.
4) Model Training (Logistic Regression)
Split the dataset into training (80%) and testing (20%) sets.
Trained a Logistic Regression model on the TF-IDF features.
Made predictions on the test set.
5) Model Evaluation
Calculated accuracy score and classification report.
Plotted a confusion matrix heatmap using seaborn to visualize predictions.
6) Visualization
Bar Chart → Showed distribution of positive & negative reviews.
Heatmap → Displayed model accuracy using a confusion matrix.
Results & Insights
The model achieved a high accuracy in classifying reviews.
TF-IDF helped extract important words from customer reviews.
Logistic Regression effectively predicted sentiment with minimal computation time.
Conclusion
This project successfully analyzed customer sentiment on women’s clothing reviews. The approach can be extended to other e-commerce platforms for customer feedback analysis, product improvement, and recommendation systems.
Matplotlib & Seaborn → Data visualization (bar chart & heatmap).

OUTPUT:
![Image](https://github.com/user-attachments/assets/fafcfadb-fb89-4a64-8625-6ce475ea43b1)

![Image](https://github.com/user-attachments/assets/cde9b554-ad0a-49ba-a6a3-a1e2b9cf792f)
