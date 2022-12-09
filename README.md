# Fashion Reccomendation 
## _A system to make your mornings easier_


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Have you ever struggled to decide what to wear in the morning? So it might not be an issue for too much longer! Don't waste those valuable minutes trying to decide what to wear—let AI do it for you with the help of this outfit recommendation system based on computer vision!

In addition to providing some fundamental information on how you might approach building a computer vision project with deep learning, this article will discuss how I went about developing a fashion recommendation system. This particular system uses individual pieces of clothing as image inputs and suggests outfits based on what it deems to be appealing combinations. It is created by combining the convolutional neural network (CNN) autoencoder, multi-input CNN, and K-Means clustering models. Using a Dataiku, the final user interface is produced.

This system is aimed at providing fashion reccomendations or in simple reccomend matching outfits once a user enters one outfit. ie: if a user enters a tshirt into the system, the system will predict and inform the user on matching trowsers to wear.



## Features

- Quick Model runtime
- PreTrained Model easy usage
- All code in one pyiby file



## Technologies Used

Dillinger uses a number of open source projects to work properly:

- [Python] - Python 3.9 used for compiling
- [Google Colab] - Google colab used because of its free and easy to use nature.
- [transformers] - Library used to import ViTFeatureExtractor, ViTForImageClassification
- [HuggingFace] - PreTrained Model retrieved through HuggingFace
