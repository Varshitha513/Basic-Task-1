**BASIC TASK-1**
 **Sentiment Analysis**: Develop a sentiment analysis tool that can analyze the sentiment (positive, negative, or neutral) of text data, such as social media posts or reviews of Restaurant reviews.
 To do this project: firstly we need to import the csv file to make the predictions and csv file named "Restaurant_Reviews".

 **Sentiment Analysis Project Description:**
1. **Problem Definition**:
The goal of this sentiment analysis project is to build a tool that can analyze the sentiment (positive, negative, or neutral) of text data, such as social media posts or reviews of restaurant reviews.

2. **Data Collection**:
Gather a labeled dataset of text data containing examples of positive, negative, and neutral sentiments. You can use datasets from sources like Twitter, IMDb movie reviews, or customer reviews for restaurants.

3. **Data Preprocessing**:
We follow the following process for the data processing
re.sub: Remove non-alphabetic characters from the text.
lower(): Convert the text to lowercase.
Tokenization: Split the text into individual words.
Stopword Removal: Remove common English stopwords using NLTK.
Stemming: Reduce words to their root form using the Porter stemming algorithm.

4. **Building a Sentiment Analysis Model:**
This part is not explicitly shown in the provided code snippet, but it is assumed that you have a trained classifier (classifier) and a vectorizer (cv). Here are the general steps:
Text Vectorization: Convert the preprocessed text data into a numerical format. In this case, it uses a CountVectorizer (cv).
Training a Classifier: Train a sentiment analysis classifier using a labeled dataset. Popular choices include Naive Bayes, Support Vector Machines, or deep learning models like LSTM or BERT.

5. **Making Predictions**:
The predict_sentiment function takes a sample review, preprocesses it, transforms it using the provided vectorizer (cv), and then makes predictions using the pre-trained classifier (classifier).

6. **Real-life Applications**:
This sentiment analysis tool can be applied in various real-life scenarios:
Brand Monitoring: Monitor social media mentions to understand public sentiment towards a brand.
Customer Feedback Analysis: Analyze customer reviews to identify areas of improvement or gauge satisfaction.
Market Research: Analyze opinions on new products or features.
Political Analysis: Understand public opinion on political issues by analyzing speeches, news, and social media.
