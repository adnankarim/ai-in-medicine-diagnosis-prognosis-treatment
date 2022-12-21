# Blood Cell Object Detection - YOLOv5

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LHqkLYXAkZXMsXt-KQEBDpaZZiPZk7zk?authuser=1#scrollTo=7mGmQbAO5pQb)

At present, detecting blood cells commonly depends on artificial counting by observing microscope slides. This process is time-consuming and requires a lot of manpower. To improve the efficiency and accuracy of blood cell detection, we used YOLOv5. 

In this project, we will cover the following material to help you create your own object detection model:

- An Overview of Object Detection
- About the YOLO v5 Model
- Collecting Our Training Images
- Annotating Our Training Images
- Installing YOLO v5 dependencies
- Downloading Custom YOLO v5 Object Detection Data
- Defining YOLO v5 Model Configuration and Architecture
- Training a custom YOLO v5 Detector
- Evaluating YOLO v5 performance
- Running YOLO v5 Inference on test images
- Exporting Saved YOLO v5 Weights for Future Inference

## Data

- We use a [public blood cell detection dataset](https://public.roboflow.ai/object-detection/bccd), which is open source and free to use. You can also use this notebook on your own data.

- All the images are in the `.jpeg` format and labels `YOLO v5 PyTorch format`.



## Model

- Model is based on [this paper](https://zenodo.org/record/7002879#.Y3U79b5BxhE).


## Results


  <img src="https://github.com/rajeevratan84/ModernComputerVision/raw/main/bccd.jpeg" alt="Result 1" style="height: 250px;width:500px;"/>

