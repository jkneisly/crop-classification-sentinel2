# crop-classification-sentinel2
This repository contains code implementations for four deep learning models used for crop classification with Sentinel-2 satellite imagery. The code and datasets were prepared as part of the Côte d'Ivoire Byte-Sized Agriculture Challenge.

Repository Structure

├── data/             # Training and test datasets
├── cnn_inception/    # CNN with inception modules and skip connections
├── cnn_gru/          # CNN-GRU hybrid model
├── hrnet/            # HRNet model
├── deeplabv3/        # DeepLabV3 model
└── README.md         # Project overview and instructions

Models Included

CNN with Inception Modules and Skip Connections (best performance)
CNN-GRU Hybrid
HRNet
DeepLabV3

Each model folder contains code for training and evaluation.
Usage



Prepare the data:
Place the training and test datasets in the data/ folder.



Run a model:
Navigate to the desired model’s folder and follow the instructions in the script or comments.



Data Source
The datasets are available from the official challenge website.
