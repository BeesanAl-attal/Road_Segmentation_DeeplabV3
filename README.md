# Road_Segmentation_DeeplabV3
# Road Segmentation Project

This project implements a road segmentation model using PyTorch. The goal of the project is to classify pixels in satellite or aerial images as road or non-road (binary classification). The model is trained on a custom dataset and is evaluated on a validation set. It uses the pre-trained model from torchvision and fine-tunes it for road segmentation.

## Requirements

- Python 3.x
- PyTorch
- NumPy
- TorchVision
- Other dependencies listed in `requirements.txt` (to be created)

## Setup

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/road-segmentation.git
    cd road-segmentation
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset from [Google Drive](https://drive.google.com/file/d/1DJWfpQA5FC0C_uWsLQHL_OzdBXztaMqn/view?usp=sharing) and place it in the `dataset/` folder.

## Project Structure

```plaintext
road-segmentation/
│
├── dataset/               # Contains the training and validation datasets
├── model.py               # Model definition file (if custom model is created)
├── train.py               # Main script for training the model
├── requirements.txt       # List of required dependencies
├── README.md              # This file
└── model.pth              # Trained model file (saved after training)
