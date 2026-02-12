# CIFAR-10 Image Classifier with Grad-CAM and Gradio

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. It includes an interactive web interface and utilizes Grad-CAM to provide visual explanations for the model's predictions.

## Project Description
The goal of this project was to build an image recognition system capable of identifying objects across 10 distinct categories. Beyond simple classification, the project incorporates explainable AI techniques to show which parts of an image the model prioritizes during inference.

### Key Components
* **Model Architecture**: A custom Convolutional Neural Network built using the PyTorch framework.
* **Explainability**: Implementation of Grad-CAM to generate heatmaps that visualize the model's focus.
* **User Interface**: A web-based application developed with Gradio for real-time image testing.
* **Processing**: Configured to utilize GPU acceleration for faster computation.


## Technical Details
* **Dataset**: CIFAR-10 (60,000 images, 32x32 pixels, 10 classes).
* **Framework**: PyTorch.
* **Training Environment**: Google Colab.
* **Accuracy**: Approximately 64%.

## File Structure
* `CIFAR10_Classifier.ipynb`: The complete Python notebook containing the training and deployment code.
* `student_model.pth`: The saved weights of the trained model.
* `requirements.txt`: A list of the Python libraries required to run the environment.


## Setup and Installation

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/[YOUR_REPO_NAME].git
