# Trip Advisor Reviews
I was given a dataset where there were given reviews and ratings based on those reviews of a Hotel on Trip Advisor. I divided my goal into two parts. I had to predict whether the given review had a positive or negative attitude. The other part of the project was to predict the rating based on the reviews. 

## Sentiment Analysis

One part of the project was to predict the positive or negative attitude of a review. These models were easier models to produce because I changed from predicting 5 different numerical ratings, I changed in predicting binary outputs (positive or negative). These made my model have a higher F1 score. The best model was the Random Forest Classifier with an F1 score of 95%. After, I converted the binary numbers and tokenized reviews back to their original form to make a predicted dataset. 

## Ratings classification

The final part of the project was predicting the ratings based on the reviews. I tokenized the reviews and removed stop words for an easier predicting ability. Then, I started using classification models to predict the ratings from 1 - 5. Most models did not do very well, until I implemented the Tensorflow Keras package. This Artificial Neural Network helped attain a high accuracy and a low loss which was ideal for the NN. The NN proved to be the best model

## Future Work

I would like to implement a Pytorch model as those are known to be the best for NLP. Unfortunately, the pytorch model was not working the best and due to limited time, I switched to the Tensorflow package. Furthermore, creating a chatbot for the reviews based on the sentiment analysis and ratings is something I can do in the future. 
