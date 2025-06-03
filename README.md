 ## 🎨 ArtGuard
ArtGuard is a deep learning-based image classification project that detects whether a given image is AI-generated or real human-made art. It uses a fine-tuned ResNet50 model and is trained on a curated dataset containing AI-generated artworks and real artworks.

##🚀 Features
Classifies artwork as AI-generated or Real Art

Uses ResNet50 pretrained on ImageNet

Fine-tuned with image augmentation for improved accuracy

Real-time prediction using uploaded images

Achieved high accuracy on both training and testing sets

##🧠 Model Architecture
Base: ResNet50 (without top layers)

Global Average Pooling

Fully connected dense layer with dropout

Output layer with sigmoid activation for binary classification

Optimizer: Adam

Loss: Binary Crossentropy

## 🧾 Dataset
AI Art Dataset (AiArtData.rar)

Real Art Dataset (RealArt.rar)
Extracted and organized into train, validation, and test directories using an 80-10-10 split.

## 📊 Training & Evaluation
Trained for 20 epochs with early stopping and checkpointing

Fine-tuned by unfreezing last 20 layers of ResNet50

## 🖼️ How to Use
Upload your image via Colab

The model will predict and display whether it's AI-generated or real

Prediction and visualization included

## ✨ Future Enhancements
Web interface using Flask

Upload multiple images for batch prediction

Integrate explainable AI (Grad-CAM)
