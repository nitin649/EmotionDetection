# Emotions Recognition System

# Description:

1.  Facial expression recognition software is a technology which uses biometric markers to detect emotions in human faces.
2.  More precisely, this technology is a sentiment analysis tool and is able to automatically detect the six basic or universal expressions: 
    happiness, sadness, anger, neutral, surprise, fear, and disgust.
3.  Facial expressions and other gestures convey nonverbal communication cues that play an important role in interpersonal relations.
4.  Therefore, facial expression recognition, because it extracts and analyzes information from an image or video feed, it is able to deliver 
    unfiltered, unbiased emotional responses as data.

# Project Structure

1. For the purpose of this project, I have used the Kaggle dataset which is a collection of 7 emotions type having 70K images for training and 7K images for validation.
2. I have trained this system only on these classes ['angry','happy','sad','surprise','neutral'] using 25k images.
3. Model Training
    - For model training I have used Convolutional Neural Networks.
    ### Model Structure
    ![model1](https://user-images.githubusercontent.com/55678844/150377030-86e6bbb1-f518-4f3b-8ef0-9f3fa22c6ed6.JPG)
    ![model2](https://user-images.githubusercontent.com/55678844/150377018-a9c87099-03aa-48d5-9698-0fc69159c917.JPG)
    ![model3](https://user-images.githubusercontent.com/55678844/150377034-b72646c7-d997-4e45-a727-6b3e2652b08f.JPG)
    
    - Overall Accuracy of this model is 92%

# Improvements
1.  For improvement we can use any ImageNet Model.
2.  We can train our model on More data. I have used only 25k but we can build and train our model using all 70k images of 7 categories.
3.  Image Augementation can also be used.
