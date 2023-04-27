# YOLOv3 Object Detection Model
This project is an implementation of the YOLOv3 (You Only Look Once version 3) object detection algorithm using PyTorch. The purpose of this project is to provide a basic understanding of how YOLOv3 works and how to implement it. The code has been done by following the [1] video tutorial.

# Dependencies
makefile
    Copy code
    matplotlib==3.4.3
    numpy==1.19.5
    Pillow==8.3.1
    torch==1.9.0
    torchvision==0.10.0
    tqdm==4.62.3
# Files
        config.py: A configuration file containing hyperparameters for the model.
        model.py: A Python module containing the YOLOv3 implementation.
        train.py: A Python script for training the YOLOv3 model.
        loss.py: A Python script for calculating the loss.
        dataset.py: A Python script for accessing the data.

# Dataset
The dataset used is the COCO (Common Objects in Context) dataset and is available on their website. The different models have been trained on the train2017 dataset for personal learning purposes.

# Notes:
  - this has been done by following the excellent tutorials from Aladdin Persson [2], the original paper [1].
  - the generated models are not maid to be used as they clearly overfit the training data.

# References

[1] - [YOLOv3 Paper](https://arxiv.org/abs/1804.02767)

[2] - [Aladdin Persson's video that has been followed to create this project](https://www.youtube.com/watch?v=Grir6TZbc1M&list=PLhhyoLH6Ijfw0TpCTVTNk42NN08H6UvNq&index=6)

