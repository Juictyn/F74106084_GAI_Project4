# F74106084_GAI_Project4

實驗環境：python 3.11.7, torch 2.2.2, cuda 12.5

以下是我在這個實驗中使用的套件

import torch

import torch.nn as nn

import torch.optim as optim

from PIL import Image

import torchvision

import matplotlib.pyplot as plt

from torchvision import transforms 

from torch.utils.data import DataLoader, Subset

import numpy as np

import torch.nn.functional as F

import math

import time

from torch.optim import Adam

from skimage.metrics import structural_similarity as ssim

資料集是從https://www.kaggle.com/datasets/chetankv/dogs-cats-images擷取下來

實驗進行時我有改動參數的碧芳皆有標示於我的ipynb檔案中，可以照著改就好！

