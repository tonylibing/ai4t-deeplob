# Price movement prediction with DL
This repository contains the code to instantiate, train, and evaluate the deep neural network architecture described in [DeepLOB model described in the paper DeepLOB: Deep Convolutional Neural Networks for Limit Order Books](https://ieeexplore.ieee.org/document/8673598) by Z. Zhang et al.

The complete pipeline to download the data, implement the dataset I/O, instantiate and train the model is contained in this [notebook](deeplob.ipynb).

## Usage
This implementation is based on Python 3.8. To install all the requirements:
```bash
$ pip install -r requirements.txt
```

## Training
To train the model from scratch, just run the entire notebook. The model automatically logs some metrics (e.g., loss, accuracy, etc.) using [WandB](https://wandb.ai/site), so make sure to log in before you start the training process.

However, the model has already been trained and you can find [here](https://wandb.ai/mikcnt/DeepLOB-ai4t) the WandB logs for it.