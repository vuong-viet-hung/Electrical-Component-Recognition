# Electrical-Component-Recognition

## I. Description
Colab Notebooks for Electrical Component Recogntion classification task.

The implementation is based on [An Electronic Component Recognition Algorithm Based on Deep Learning with a Faster SqueezeNet](https://www.hindawi.com/journals/mpe/2020/2940286/).

## II. Dataset
The dataset is obtain from Kaggle's [ECAD dataset](https://www.kaggle.com/datasets/mrojer/electronic-components-for-automatic-detection), which contain images of 11 electrical components and background.

## III. Experiment
1. Download your Kaggle API token from your Kaggle profile site. [Instructions](https://www.kaggle.com/docs/api).
2. Execute the **Dataset Preparation/Dataset Preparation.ipynb** notebook to download and prepare the dataset, you'll be prompted to upload your Kaggle API token.
3. You can the proceed to train your model using one of these implementation: Using PCA and SVM (**PCA + SVM/PCA+SVM.ipynb**), SqueezeNet (**SqueezeNet/SqueezeNet.ipynb**)