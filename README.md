# Sentimental_Analysis.
This sentiment analysis project uses Twitter and Reddit data to determine the sentiment of posts and comments.<br>

**Project Overview**<br>
The project uses natural language processing (NLP) techniques to analyze the sentiment of text data. Specifically, it employs a pre-trained machine learning model to classify text data as positive, negative, or neutral. The project extracts data from Twitter and Reddit, preprocesses it, and applies the pre-trained model to predict the sentiment of each post or comment.<br>

**Project Structure**<br>
The project is organized into three main folders:

+ data: This folder contains the raw data extracted from Twitter and Reddit. The data is stored in CSV format, with each row representing a single post or comment.<br>

+ preprocessing: This folder contains the scripts used to preprocess the raw data. The preprocessing steps include text cleaning, tokenization, and stop word removal. The preprocessed data is stored in a separate CSV file for each platform.<br>

+ model: This folder contains the pre-trained machine learning model used for sentiment classification. The model is a deep neural network trained on a large corpus of text data.<br>

**Getting Started**<br>
To run the sentiment analysis project, follow these steps:

Clone the project repository to your local machine.<br>
Install the required packages listed in the requirements.txt file.<br>
Extract the raw data from Twitter and Reddit and save it in the data folder as twitter_data.csv and reddit_data.csv, respectively.<br>
Run the preprocessing scripts in the preprocessing folder to preprocess the data.<br>
Run the sentiment analysis script in the model folder to classify the sentiment of each post or comment.<br>

**Conclusion**
This sentiment analysis project demonstrates the use of NLP techniques and machine learning to analyze the sentiment of text data from social media platforms. The project can be easily extended to include other platforms such as Facebook, Instagram, or TikTok, and can be adapted to analyze the sentiment of specific topics or events.<br>
