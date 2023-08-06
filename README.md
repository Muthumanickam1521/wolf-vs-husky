# WOlf Vs. Husky Image Classifier

An image classifier built using deep learning in Python that has potential to predict whether an image has wolf or husky.

## Problem
I find hard to distinguish bewteen a wolf and a hsuky as they are morphologically similar. I see this as a reasonable problem to be solved using data science techniques. 

## Usage
[Link to App](https://wolf-vs-husky.streamlit.app/)
1. Click on "Link to App"
2. Upload an image that contains either wolfs or huskies
3. Obtain predictions at the bottom

## Data
[Samples of wolf](https://images.cv/dataset/white-wolf-image-classification-dataset)

[Samples of husky](https://images.cv/dataset/siberian-husky-image-classification-dataset)

Without image augmentation, the image dataset possessed 1200 samples of each animal.

## Model
A simple single layered Convolutional Neural Network (CNN) was called and used to build a deep learning model. Why single layer network is because of unavailability of sufficient computational resources.

## Deployment
The model is given a minial user interaface using Streamlit python library. I created a simple data app and deployed it in cloud space offered by streamlit. The app contains an image file uploader. 

## Future work
Though the model identifies 98% accurate, it is not a robust model since it was built with a samll dataset and a single layer CNN. In future versions of this project, i will work on improving other benchmarks such as precision.
