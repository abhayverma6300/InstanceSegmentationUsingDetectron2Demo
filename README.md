# Phone Instance Segmentation using Detectron2

## Overview
This repository contains Python code for performing instance segmentation on mobile phone images using Detectron2. The code includes functions for preparing the dataset, training the model, performing inference, and visualizing the results.

## Files
- `phone_instance_segmentation.ipynb`: Jupyter Notebook containing the main code for phone instance segmentation.
- `README.md`: Documentation file explaining the code and its components.

## Dependencies
- Python 3.x
- Libraries: detectron2, cv2, numpy, matplotlib, torch, torchvision

## Setup
1. Install the required dependencies:
    ```
    !python -m pip install pyyaml==5.1
    !python -m pip install 'git+https://github.com/facebookresearch/detectron2.git'
    ```
2. Open and run the `phone_instance_segmentation.ipynb` Jupyter Notebook for detailed execution.

## Code Structure
- `get_phone_dicts`: Function to prepare dataset dictionaries containing annotations for each image.
- Model training and configuration using Detectron2.

## Usage
1. Execute the code cells in sequential order to train the model and perform inference.
2. Visualize the segmentation results on sample images.

## Additional Information
- Experiment with different model configurations or datasets for specific use cases.


