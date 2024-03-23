# YOLOv8 Training for Driving License Detection
This repository contains code and instructions for training a YOLOv8 model to detect driving licenses using the dataset provided by UTAR PRUK1 via Roboflow. The trained model can be used to detect driving licenses in images or videos.

# Dataset Information
The dataset used for training can be found here. It contains annotated images of Malaysian driving licenses, suitable for training object detection models.
https://universe.roboflow.com/utar-pruk1/malaysia-driving-license
![image](https://github.com/chunhonglam/Malaysia-Driving-License-Object-Detection-Training/assets/81572035/3532cfe9-5196-485b-8626-ad10b62b73b3)

# Training Steps
Data Preprocessing: Download the dataset from the provided link. Optionally, you can use Roboflow's online platform to preprocess and augment the data.
![image](https://github.com/chunhonglam/Malaysia-Driving-License-Object-Detection-Training/assets/81572035/88cde449-5efd-43c9-9d68-25e5534931ed)

Configuration: Modify the YOLOv8 configuration file according to your requirements. Adjust parameters such as batch size, learning rate, and model architecture.
![image](https://github.com/chunhonglam/Malaysia-Driving-License-Object-Detection-Training/assets/81572035/2ad318c7-7db3-4f5f-a85a-f7f07f638dbd)

Training: Train the YOLOv8 model using the preprocessed dataset. You can train the model locally or using cloud services like Google Colab or AWS.
![image](https://github.com/chunhonglam/Malaysia-Driving-License-Object-Detection-Training/assets/81572035/066a8bee-010a-48a1-9d2c-e621d16a155a)

Evaluation: Evaluate the trained model using metrics such as precision, recall, and mAP (mean Average Precision) to assess its performance.
![image](https://github.com/chunhonglam/Malaysia-Driving-License-Object-Detection-Training/assets/81572035/e0c247e2-f25f-4f24-9f56-1f20b335c139)

Deployment with Roboflow: This model can be easily deployed using Roboflow's deployment infrastructure. Roboflow provides an end-to-end platform for training, deploying, and managing computer vision models. Once trained, you can deploy your model directly from Roboflow to integrate it into your applications.


# Sample Implementation
![image](https://github.com/chunhonglam/Malaysia-Driving-License-Object-Detection-Training/assets/81572035/2398bd5a-4642-48a3-80ca-b82b76e67864)
