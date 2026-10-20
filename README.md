# Rice Grain Variety Classifier

A computer vision project that uses deep learning and transfer learning to classify images of rice grains into five distinct varieties. Built with PyTorch and ResNet18, the system includes an image preprocessing pipeline and an interactive Gradio interface for real-time inference.

## Features

- **Transfer Learning:** Fine-tuned a ResNet18 convolutional neural network for rice grain variety classification.
- **Image Preprocessing:** Uses torchvision transforms for image resizing, center cropping, and RGB normalization.
- **Multi-Class Classification:** Predicts one of five rice grain varieties from an input image.
- **Interactive Interface:** Provides a Gradio web interface for uploading images and viewing predictions.
- **Confidence Scores:** Displays prediction confidence scores for the supported rice grain classes.
- **Real-Time Inference:** Processes uploaded images and returns model predictions interactively.

## Tech Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| Deep Learning Framework | PyTorch |
| Model Architecture | ResNet18 |
| Image Processing | torchvision |
| Web Interface | Gradio |

## How It Works

1. **Image Input:** The user uploads an image of a rice grain sample.
2. **Preprocessing:** The image is resized, center-cropped, converted to RGB, and normalized using torchvision transforms.
3. **Model Inference:** The processed image is passed to the fine-tuned ResNet18 model.
4. **Classification:** The model generates scores for the five rice grain varieties.
5. **Results:** The Gradio interface displays the predicted class and confidence scores.
