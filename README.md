# fake_news_classifier_lstm
 This project classifies fake news with textual content using LSTM network. 
 
 # objective 
 Fake news classification on social media has gained a lot of awareness in the last decade due to the ease of adding fake content through social media. Therefore detecting false information quickly is crucial more than ever.

# dataset
The dataset is from a Kaggle competition. Dataset has 20800 entries and 5 columns listed as below.
id: unique id for a news article title: the title of a news article author: author of the news article text: the text of the article; could be incomplete label: a label that marks the article as potentially unreliable
- 1: unreliable 
- 0: reliable

The labels are binary, which indicates if each article is fake or not.

 # approach 
 This project classifies fake news with textual content into 2 categories (0: reliable, 1:unreliable) using deep learning.
 The model used in this system is a 5-layer LSTM model with about 1.4M parameters to train. The proposed model involves sequential processing of the data for learning. This sequential process is justified by its ability to retain a memory of what came before the current sequence being processed.
