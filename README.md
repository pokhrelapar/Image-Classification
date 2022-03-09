# Image-Classification


This is a LeNet CNN  model based image classifier that uses the GTSRB database. The German Traffic Sign Recognition Benchmark (GTSRB) contains 43 classes
of trafficsigns,split into 39,209 training images and 12,630 test images. You can donwload the database from https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

This project was done in Google Colab, but you can mirror the project in a virtual enviornment by isntall neccessary depenencies.

## Donwloading the GTSRB database
1. To download the dataset directly into you colab notebook, use **!pip install opendatasets** to download datasets from online sources like Kaggle and Google Drive.
2.  You will need a kaggle account and use the download link from above. You will also require a Kaggle key which can be generated by using request API token in your kaggle           account. https://www.kaggle.com/docs/api

### Libraries used
import numpy as np \n
import pandas as pd \n
import tensorflow as tf (Tensorflow version 2.8.0)
import seaborn as sns
import keras
import cv2
import time
import warnings
import matplotlib.pyplot as plt
import os
import pathlib
import sklearn

from matplotlib import pyplot
from PIL import Image
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report


