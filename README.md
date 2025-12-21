# Oral Cancer Detection

This project uses a YOLOv8 model to detect oral cancer from images.

## Setup

1.  **Install Dependencies**
    Ensure you have Python installed. Install the required packages using:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Directory Structure**
    - `Model/`: Contains the trained YOLO model (`best.pt`).
    - `test_data/`: Contains test images and labels.
        - `images/`: Test images.
        - `labels/`: Corresponding labels.
    - `inference.ipynb`: Jupyter notebook for running inference.

## Usage

1.  Open the `inference.ipynb` notebook:
    ```bash
    jupyter notebook inference.ipynb
    ```
2.  Run the cells to load the model and perform inference on the test images located in `test_data/images`.
3.  The notebook will display the images with detected bounding boxes.

## Model
The model is located at `Model/best.pt`.