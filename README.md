# cats-dogs-classification-CNN

## Task
We are focussed on image classification problem. We are given 25000 images of labelled cats vs dogs and we are tasked with classifying the test data - which is 12500 unlabelled images.

## Models Used

In this competition, we explored various models and techniques to improve classification accuracy. Here are the models we experimented with:

Convolutional Neural Network (CNN):

- Architecture: We utilized a deep CNN with multiple convolutional and pooling layers followed by fully connected layers.
- Training: The model was trained on the provided dataset, including data augmentation techniques such as rotation, resizing, and horizontal flipping.
- Results: The CNN achieved an accuracy of 85% on the validation set.
- Transfer Learning with Pretrained Models:

Models: 
- We experimented with pretrained models such as VGG16, ResNet50, and InceptionV3.
- Fine-tuning: We fine-tuned the models on the competition dataset by freezing the initial layers and training the remaining layers.
- Results: The best performing model was InceptionV3, which achieved an accuracy of 90% on the validation set.

## Result
The model was trained on 20000 images of dogs and cats, validated on the rest of the 5000 pictures, and ultimately achieved over 99% accuracy on the validation set.
