# Dog-NeuralNetwork_Proj
Multi-class dog breed image classifier

This notebook use Tensorflow (version 2.0) and Tensorflow Hub to build an end-to-end multi-class dog breed image classifier.

## 1. Problem
Identify the breed of a dog given an image

## 2. Data
The data we're using is from Kaggle
[Kaggle Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/data)

## 3. Evaluation
The evaluation is a file with prediction probabilities for each dog breed of each test image

For each image in the test set, you must predict a probability for each of the different breeds. The file should contain a header and have the following format:
```
id,affenpinscher,afghan_hound,..,yorkshire_terrier
000621fb3cbb32d8935728e48679680e,0.0083,0.0,...,0.0083
etc.
```

## 4. Features
Some information about the data:
* We're dealing with images (unstructured data) so it's porobably better if we use deep learning/ transfer learning
* There are 120 different classes (breeds of dogs)
* There are around 10'000+ images in the training set (these images have labels)
* There are around 10'000+ images in the test set (these images have no labels because we'll want to predict them)
