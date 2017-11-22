# Yelp-dataset-analysis
This project is to nail down best ML models to predict customers' rating stars by analyzing their text reviews. We use the public Yelp Dataset, but a slice of the data. More precisely, we only analyze data for Chinese restaurants across the US.
The very first step is to transform a text into a list of key words, which can potentially reveal a reviewer's opinion/bias on the restaurant under review. In the next step, we use the Natual Language Processing model Word2Vec, to transform the list of key words to vectors in some high dimensional space. This transform/map represent the relavence of the words in the context. With the processed data, we are going to design and test various models in terms of accuracy of prediction.  
