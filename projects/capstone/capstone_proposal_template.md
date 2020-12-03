# Machine Learning Engineer Nanodegree
## Capstone Proposal
Shvet Chakra
December 3rd, 2020

## Proposal
Emotion recognition using facial expressions
### Domain Background
Facial expressions and related changes in facial patterns give us information about the emotional state of the person and help to regulate conversations with the person. Moreover, these expressions help in understanding the overall mood of the person in a better way. Facial expressions play an important role in human interactions and non-verbal communication. Classification of facial expressions could be used as an effective tool in behavioural studies and in medical rehabilitation. Facial expression analysis deals with visually recognizing and analyzing different facial motions and facial feature changes.[1]

**Motivation**
Nowadays, when technology has penetrated into the personal life of humans with mobile devices and interaction of machines with humans is carried out on the daily basis, it is getting important for the machine to recognize the emotion of the fellow human while interating with him. Recognition of emotion can help machines powered with artificial intelligence to enhance this interaction.
Possible application where this project can be helpful in wellbeing of humans. As recognition & acceptance is the first step of any problem, this solution can help the user about their mood and help them in taking appropriate step. For eg. we have facial recognition phone security feature to lock/unlock the device, if the device captures the face and determine the emotion of the users on several intervals and then give a happy mood percentage for the day. It can help them in recognizing about their mood if it is not appropriate and motivate them to take necessary action.

### Problem Statement

Facial expressions play an important role in recognition of emotions and are used in the process of non-verbal communication, as well as to identify people. They are very important in daily emotional communication, just next to the tone of voice [2]. They are also an indicator of feelings, allowing a man to express an emotional state [3]. People, can immediately recognize an emotional state of a person. As a consequence, information on the facial expressions are often used in automatic systems
of emotion recognition [4]. The aim of the project is to recognize seven basic emotional states: neutral, joy, surprise, anger, sadness, fear and disgust based on facial expressions.[5]
Numerous investigators have used neural networks for facial expression classification. The performance of a neural network depends on several factors including the initial random weights, the training data, the activation function used, and the structure of the network including the number of hidden layer neurons, etc. Here I will try to create a CNN based nueral network model to classify the images into their seven basic emotional states: neutral, joy, surprise, anger, sadness, fear and disgust.

### Datasets and Inputs
The project has been chosen from a kaggle competion and hence the same datset will be used here also to train and test the model for the proposed problem. https://www.kaggle.com/c/emotion-detection-from-facial-expressions/data

### Solution Statement
Convolution networks or convolution neural networks are a specialized kind of neural networks for processing data that has a known grid-like topology. Examples inclued time-series data and image data which has a grid like structure. Convolution leverages three important ideas that can help  improve a machine learning system; sparse interctions, parameter sharing and equivariant representations. Moreover, convolution provides a means for working with inputs of variable sizes.
One major advantage of using CNNs over NNs is that you do not need to flatten the input images to 1D as they are capable of working with image data in 2D. This helps in retaining the “spatial” properties of images.

### Benchmark Model
_(approximately 1-2 paragraphs)_

In this section, provide the details for a benchmark model or result that relates to the domain, problem statement, and intended solution. Ideally, the benchmark model or result contextualizes existing methods or known information in the domain and problem given, which could then be objectively compared to the solution. Describe how the benchmark model or result is measurable (can be measured by some metric and clearly observed) with thorough detail.

### Evaluation Metrics
_(approx. 1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model. The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution. Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable). Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design
Technically, deep learning CNN models to train and test, each input image will pass it through a series of convolution layers with filters (Kernals), Pooling, fully connected layers (FC) and apply Softmax function to classify an object with probabilistic values between 0 and 1. The below figure is a complete flow of CNN to process an input image and classifies the objects based on values.


-----------

##References:
[1] https://biomedical-engineering-online.biomedcentral.com/articles/10.1186/1475-925X-8-16
[2] Ratliff M. S., Patterson E., Emotion recognition using facial expressions with active appearance
models, Proceedings of the Third IASTED International Conference on Human Computer
Interaction, ACTA Press, Anaheim, CA, USA, 2008, 138–143.
[3] Tian Y. I., Kanade T., Cohn J. F., Recognizing action units for facial expression analysis, IEEE
Transactions on Pattern Analysis and Machine Intelligence, 23 (2001), no. 2, 97–115.
[4] Mao Q., Pan X., Zhan Y., Shen X., Using Kinect for real-time emotion recognition via facial
expressions, Frontiers Inf Technol Electronic Eng, 16 (2015), no. 4, 272–282.
[5]International Conference on Computational Science, ICCS 2017, 12-14 June 2017,Zurich, Switzerland
Emotion recognition using facial expressions, Paweł Tarnowski, Marcin Kołodziej, Andrzej Majkowski, Remigiusz J. Rak

