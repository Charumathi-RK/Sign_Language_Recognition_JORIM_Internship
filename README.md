# Sign_Language_Recognition_Using_ROBOFLOW
Internship Task at Jorim Technology Solutions

## Project Overview
This project leverages the Roboflow 3.0 Object Detection (Fast) model to detect and classify sign language gestures from images or video streams. It utilizes Roboflow for dataset management and deployment. The model is trained to achieve high accuracy with mAP 94.3%, precision 86.1% and recall 91.1%. 

## Features

- Real-time Inference: Run inference on images, videos, or webcam streams.
- High Accuracy: Achieves top-tier performance on sign language gesture recognition.
- Easy Integration: Simple steps to deploy and integrate into your applications.

## Table of Contents
1. Installation
2. Getting Started
3. Usage
4. Model Training
5. Model Evaluation
6. Conclusion
   
## Installation
Before you can use the project, you'll need to set up the development environment. Follow these steps:

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Steps
1. Clone the repository
   ```
   git clone https://github.com/Charumathi-RK/Sign_Language_Recognition_Using_ROBOFLOW.git
   cd sign-language-detection
   ```
3. Set up a virtual environment (optional but recommended)
    ```
    python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
5. Install the required dependencies
   ```
   pip install -r requirements.txt
   ```

## Getting Started
To use this project, you'll need to set up the necessary API keys for Roboflow and load your pre-trained model.

### Set Up API Keys:

Go to Roboflow and get your API key.
Create a .env file in the root of the project and add your API key:
```
ROBOFLOW_API_KEY=your_api_key_here
```
The model is deployed on Roboflow. Use the provided API to load and deploy the model.

## Usage

To run inference on an image or video:

Run Inference on Image
- Create a Python script (inference.py):
   -- Refer SignLanguageRecognitionWithRoboflow.zip file

## Model Training
### Dataset Details: 

![data](https://github.com/user-attachments/assets/a26c7b0e-8f5b-484d-a228-790c62d7c985)


### Model Type:
#### Roboflow 3.0 Object Detection (Fast)

### Training Graphs

![TRAINING GRAPGHS](https://github.com/user-attachments/assets/0812e434-93f7-4309-9358-987c086bb385)



## Model Evaluation

1.mAP 

![mAP](https://github.com/user-attachments/assets/f524f605-e7e3-4bc3-8d19-5b3f8e1da644)

2. Box loss, Class loss and Object loss Graphs

![lossGraphs](https://github.com/user-attachments/assets/a929ad80-7e5d-4572-a622-e72014079c9a)

3. Perfomance By Class

   ![performancebyclass](https://github.com/user-attachments/assets/67c68ca6-8a9d-43dc-8916-492c76f3aa12)

## Sample Output

### In Roboflow:

![sample output](https://github.com/user-attachments/assets/82c03262-96e4-4925-8767-5832de583cf2)

### In Local System: (VSCode)

![sample output vscode](https://github.com/user-attachments/assets/d62bf3c1-b256-43aa-9f8b-26ea1fc19440)

### In Google Colab Notebook:

![sample output colab](https://github.com/user-attachments/assets/4ea1b956-0af9-4198-8d2b-7c46576b25a1)


## Acknowledgments
- Roboflow for providing the tools and dataset management platform.
- YOLOv11 for object detection model capabilities.
- The open-source community for their contributions.

## Conclusion
This Sign Language Recognition project demonstrates the effectiveness of combining advanced object detection models like YOLOv8 with the power of Roboflow for real-time gesture recognition. By achieving remarkable performance metrics—mAP of 94.3%, Precision of 86.1%, and Recall of 91.1%—the project showcases its potential for applications in accessibility technologies and communication for individuals with hearing impairments.

### Key Insights:
- #### High Performance: The trained model delivers superior accuracy and efficiency, making it suitable for real-time applications such as sign language interpretation.
- #### Robust Dataset Management: Utilizing Roboflow for dataset preparation, management, and deployment simplifies the workflow, enabling rapid prototyping and deployment.
- #### Scalability: The solution is easily scalable to include additional gestures or adapt to other vision-related tasks, with the option for local or cloud-based deployment.
- #### Flexibility: The project is designed for simple integration with web and mobile applications, supporting real-time inference from images, videos, or webcam streams.
  
### Future Enhancements:
- #### Gesture Expansion: Adding more sign language gestures or expanding the dataset for broader recognition.
- #### Edge Deployment: Further optimizations for running on resource-constrained devices, such as mobile phones or embedded systems.
- #### Multi-Modal Integration: Exploring the use of additional sensors (such as depth cameras) for improved accuracy in complex environments.
  
Overall, this project provides a foundation for creating practical, real-time applications that can assist individuals with disabilities, enhance communication, and empower sign language recognition systems.

## REFERENCES:

1. [Dataset of phrases in Indian Sign Language](https://data.mendeley.com/datasets/y8vg69brn2/1)
   
    Saipatwar, Saksham; Wattamwar, Aditya; Saindane, Harshwardhan; Patil, Tushar; Tiwaskar, Shweta (2024), “Dataset of phrases in Indian Sign Language”, Mendeley Data, V2, doi: 10.17632/w7fgy7jvs8.2

2. [Sign-Language-Generation-From-using-YOLOv5](https://github.com/entbappy/Sign-Language-Generation-From-Video-using-YOLOV5)
 
 -Source : GitHub

3. [Roboflow.com](https://roboflow.com/)

###Platforms/Tools used:
- [Google Colab](https://colab.research.google.com/)
- [Roboflow.com](https://roboflow.com/)
- [Ultralytics - YOLO](https://docs.ultralytics.com/models/yolo11/)
- LabelImg -Annotation Tool
