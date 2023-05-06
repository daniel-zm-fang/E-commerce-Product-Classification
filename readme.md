# E-commerce Product Classification

Link to Kaggle competition: <https://www.kaggle.com/competitions/uw-cs480-winter23>

## Goal

The goal is to classify products into 27 categories. The dataset contains ~43000 products, each product has its categorical, text, and image data.

The competition uses accuracy as the evaluation metric. Thus the goal is to maximize the accuracy of the model.

## Environment & Setup

* Python version: Python 3.9.16
* enviornment: Google Colab (GPU)
* directory structure on Colab:

```{bash}
.
├── train.csv           (categorical & text data of products)
├── test.csv            (categorical & text data of products)
├── noisy-images.zip    (train & test images of products)
├── ensemble.ipynb      (main notebook)
```
