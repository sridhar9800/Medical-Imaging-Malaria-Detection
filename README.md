# Malaria Image Analysis using CNNs
Designing and developing a CNN for malaria image analysis

This Deep learning + medical imaging system can help reduce the 400,000+ deaths per year caused by malaria.

# Data Characteristics
Size – 407.5 MB

Source – National Library of Medicine

Shape –  The dataset contains a total of 27,558 cell images with equal instances of parasitized and uninfected cells

Labelled Target – (Parasitized/Uninfected)

# Steps
1. Downloaded data and cleaned and organized the images.

2. Feature extraction using pretrained neural networks - VGG 16
![Alt text](FE.png?raw=true "FE.png")

3. Defining a model - Basic Vs. Multilayer Perceptron - A classifier that sits on top of the feature extractor.
# Best Model Metrics
![Alt text](BestModel.png?raw=true "BestModel.png")

4. Visuvalize the predictions
![Alt text](Prediction.png?raw=true "Prediction.png")

5. Future Work:

        Try Conv2d and Max Pooling with strides
        Augment the data to prevent overfitting 
        Also considering using an All-CNN model as it generally performs significantly better than VGG-16.

