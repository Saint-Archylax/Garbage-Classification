Garbage Classification Mobile Application Using MobileNetV2 and EfficientNet-B0

Undergraduate research project that classifies waste images into six categories—cardboard, glass, metal, paper, plastic, and trash—using deep learning and transfer learning techniques. The project was developed and deployed as a mobile application, allowing users to capture or upload images directly from their mobile devices for real-time waste classification.

The study evaluates the performance of MobileNetV2 and EfficientNet-B0 models using the TrashNet dataset and demonstrates the feasibility of lightweight deep learning models for mobile-based environmental applications.

Live Demo: https://peppy-torte-2d72dd.netlify.app

Features
Mobile-friendly waste classification application
Capture images using a mobile device camera
Upload waste images for classification
Real-time prediction using a trained deep learning model
Supports six waste categories:
Cardboard
Glass
Metal
Paper
Plastic
Trash
Results
Model	Accuracy	F1 Score (Macro)	Parameters
MobileNetV2	84.74%	0.8306	2.27M
EfficientNet-B0	89.21%	0.8795	4.06M

Dataset: TrashNet (2,527 images)

Project Structure
app/ — Mobile application interface and TensorFlow.js implementation for in-browser inference
notebooks/ — Model training, evaluation, and conversion notebooks
trained_models/ — Trained Keras model files
Technologies Used
Python
TensorFlow
TensorFlow.js
MobileNetV2
EfficientNet-B0
HTML, CSS, JavaScript
Netlify
