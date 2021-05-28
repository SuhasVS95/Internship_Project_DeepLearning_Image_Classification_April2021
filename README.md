# Internship_Project_DeepLearning_MedTourEasy_April2021

This is a project that I had completed as a part of intership at MedTourEasy in the month of April, 2021.

Problem Statement:

American Sign Language (ASL) is the primary language used by many deaf individuals in North America, and it is also used by hard-of-hearing and hearing individuals. The language is as rich as spoken languages and employs signs made with the hand, along with facial gestures and bodily postures.We are supposed to train a convolutional neural network(CNN) to classify images of American Sign Language (ASL) letters. After loading, examining, and preprocessing the data. We have just taken 3 lables to classify ['A','B','C'] which is already encoded as 0,1,2.


Tasks Completed:

1. We divided the data into training and test sets with 1600 and 400 images respectively.
2. Visualised the training data and familiarised with the sign symbols.
3. Labels 'A', 'B' and 'C' are encoded as 0, 1, and 2, respectively for both train and test datasets.
4. Defined a convolutional neural network to classify the data.
5. Compiled the model with the 'adam' optimizer, 'categorical_crossentropy' as the loss function, and 'accuracy' as a metric.
6. Trained the data with the arguments x_train,y_train_encoded,epochs=2.
7. The model is a good fit with an accuracy of ~99% on both the train and test datasets.
8. Visualised the model prediction mistakes which were only 2 misclassifications.
