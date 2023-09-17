# YOLOv3 Object Detection using Keras

![YOLOv3](yolov3.png)

## Overview

This project demonstrates the implementation of YOLOv3 for object detection using Keras. You will learn how to load pre-trained weights, perform object detection on an image, and visualize the results.

## Prerequisites

To run the Jupyter Notebook successfully, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV
- NumPy

You can install the required packages using `pip`:

```bash
pip install opencv-python numpy
```

Additionally, the notebook uses some external files and pre-trained weights, which are downloaded during the notebook execution.

## Notebook Contents

1. **Setup:** Initial setup and installing necessary packages.
2. **Configuration:** Setting up configuration parameters for object detection (IoU threshold, objectness threshold, anchor boxes, etc.).
3. **Downloading Weights:** Downloading pre-trained YOLOv3 weights from the internet.
4. **Loading Model:** Creating a YOLOv3 model in Keras and loading the pre-trained weights.
5. **Object Detection:** Performing object detection on an example image.
6. **Visualization:** Visualizing the detected objects in the image.
7. **Saving Output:** Saving the image with detected objects.

## Usage

1. **Clone the Repository:**

   Clone this GitHub repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. **Navigate to the Notebook:**

   Go to the directory where the Jupyter Notebook (`Yolo_v3_Object_Detection_using_Keras.ipynb`) is located.

3. **Run the Notebook:**

   Open and run the notebook cell by cell, following the instructions and code provided.

4. **Object Detection:**

   You can use this notebook to perform object detection on your own images. Simply replace the `image_path` variable with the path to your image.

## Model Architecture

The YOLOv3 model architecture is used for object detection. The notebook loads pre-trained weights that have been trained on the COCO dataset, making it capable of detecting 80 different object classes.

## Results

After running the notebook, you will be able to visualize the detected objects in your chosen image. The detected objects will be outlined with bounding boxes, and the confidence scores for each detection will be displayed.


## Acknowledgments

- The YOLOv3 model weights are provided by [pjreddie.com](https://pjreddie.com/media/files/yolov3.weights).

## Contact

If you have any questions or suggestions, please feel free to contact us at [sumantkale1999@gmail.com](mailto:sumantkale1999@gmail.com).

