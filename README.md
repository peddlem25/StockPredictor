Open In Colab
This is a regression lines to predict stock prices using Python
GE Stock price currntly Trading at $8.80 Sept 4, 2019
First let's import all of the necessary packages we need, which include NumPy, Pandas, Matplotlib, Scikit-learn and Keras/Tensorflow.
In [0]:
# Import necessary packages
import numpy as np
import pandas as pd

import matplotlib.pyplot as plt
%matplotlib inline

import sklearn
from sklearn.linear_model import Ridge
from sklearn.ensemble import GradientBoostingRegressor
from sklearn.preprocessing import MinMaxScaler

import tensorflow as tf
import keras
from keras.models import Sequential
from keras.layers import Conv1D, LSTM, Dense
from keras.callbacks import LearningRateScheduler
from tensorflow.keras.losses import Huber
from keras.optimizers import SGD
Using TensorFlow backend.
