
# Internship(MedTourEasy) Project DeepLearning - American Sign Language Classification

## Demo:

https://user-images.githubusercontent.com/70081663/120382607-78afa680-c341-11eb-8d72-ea06c83acb87.mp4


## Problem Statement:

American Sign Language (ASL) is the primary language used by many deaf individuals in North America, and it is also used by hard-of-hearing and hearing individuals. The language is as rich as spoken languages and employs signs made with the hand, along with facial gestures and bodily postures.We are supposed to train a convolutional neural network(CNN) to classify images of American Sign Language (ASL) letters. We have just taken 3 lables to classify ['A','B','C'] which is encoded as 0,1,2.


## Tasks Completed:

1. Importing the required packages and loading the data	
2. Visualize the training data	
3. Examine the Dataset	
4. One-Hot Encode the Data	
5. Define the Model	
6. Compile the model	
7. Train the model	
8. Test the Model	
9. Visualize Mistakes

## Visualize the actual signs A,B,C:

![image](https://user-images.githubusercontent.com/70081663/119942028-f759bc00-bfae-11eb-84f3-670cc67edc6f.png)

## Model Accuracy: ~ 99% on both train and test data without overfitting.

## Visualize the misclassified signs:

![image](https://user-images.githubusercontent.com/70081663/119942366-5a4b5300-bfaf-11eb-9d38-719d67b6d550.png)

## Conclusion:

1. We divided the data into training and test sets with 1600 and 400 images respectively.
2. Visualised the training data and familiarised with the sign symbols.
3. Labels 'A', 'B' and 'C' are encoded as 0, 1, and 2, respectively for both train and test datasets on which one-hot encoding is performed.
4. Defined a convolutional neural network to classify the data.
5. Compiled the model with the 'adam' optimizer, 'categorical_crossentropy' as the loss function, and 'accuracy' as a metric.
6. Trained the data with the arguments x_train,y_train_encoded,epochs=2.
7. The model is a good fit with an accuracy of ~99% on both the train and test datasets.
8. Visualised the model prediction mistakes which were only 2 misclassifications.

NOTE: I have also deployed using streamlit web app using ngrok tunneling approach to link the local system to web. 
Please refer the the web app jupyter notebook and also the demo working.

Credits: Web App deployment is inspired from the work of Nachiketa Hebbar.
Link: https://www.youtube.com/watch?v=Q1NC3NbmVlc

