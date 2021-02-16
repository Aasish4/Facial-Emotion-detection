# Facial Emotion detection
An face emotion recognition system comprises of two step process i.e. face detection (bounded face) in image followed by emotion detection on the detected bounded face. The following two techniques are used for respective mentioned tasks in face recognition system.

  * Face detection using MTCNN: It is a convolution neural network based face detection algorithm, which I have separately shown in another repository. 
    [Face detection using MTCNN](https://github.com/Aasish4/Face-detection-using-MTCNN)
    
  * Mini Xception CNN: We will train a classification CNN model architecture which takes bounded face (48x48 pixels) as input and predicts probabilities of 7 emotions in the           output layer.
## Requirements
### Dataset
The dataset used for training is [FER2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data), which can be easily downloaded from kaggle. Download the dataset and extract the content into ./data folder.


