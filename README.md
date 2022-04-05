# CA06-kNN-Movie-Recommender-Model
I used KNeighborsClassifier from sklearn to build a back-end recommender system.
After importing and cleaning dataset, I seperated it into feature and target variables and found 5 movies that has similar review scores as "The Post."

Packages used:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.neighbors import KNeighborsClassifier
