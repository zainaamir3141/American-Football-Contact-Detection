# Player Contact Detection in American Football

## Project Overview
This project focuses on the detection of player contact in American football using various machine learning and deep learning models. The goal is to evaluate and compare the performance of different models in accurately identifying player contacts from video footage.

## Repository Structure
- **preprocessing.ipynb**: Notebook for preprocessing video data into image frames, which are then categorized into 'contact' and 'non-contact' folders.
- **svm and svm_gamma_combination2**: Contains SVM implementation for predicting player contact based on the input frames.
- **player_detection_using_mmdetection.ipynb**: Investigates the performance of state-of-the-art object detection models on cropped versus uncropped images.
- **resnet50_no_augmentation**: Utilizes the ResNet-50 model for training and predicting player contact, without data augmentation.
- **contact_detection_models**: Features results from using the EfficientNet model, with discussions on model output adjustments.

## Key Findings
- **Baseline Model**: SVM served as the baseline model for detecting player contacts.
- **Deep Learning Models**: ResNet-50, ResNet-152, and EfficientNet-B0 were compared. ResNet-50, with image augmentation, achieved the highest accuracy, indicating significant potential for improving model performance against overfitting.
- **Object Detection Performance**: The research explored the efficacy of advanced object detection frameworks like Faster RCNN, Mask2Former, and YOLOX on different image scales. YOLOX demonstrated superior performance, suggesting its suitability for real-time contact detection systems in sports analytics.

## Technologies Used
- **Python**: Primary programming language.
- **Jupyter Notebook**: Used for interactive development and presentations.
- **Scikit-learn, TensorFlow, PyTorch**: Main libraries for machine learning and deep learning.
- **MMDetection**: A toolkit for object detection with pre-built models.

## Getting Started
To get a local copy up and running, follow these simple steps:

1. **Clone the repo**:
   ```sh
   git clone https://github.com/your-github-username/your-repo-name.git
