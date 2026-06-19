Garbage Classification Using MobileNetV2 and EfficientNet-B0
Undergraduate research project. Classifies waste images into six categories — cardboard, glass, metal, paper, plastic, trash — using MobileNetV2 transfer learning, compared against EfficientNet-B0.

Live demo: https://peppy-torte-2d72dd.netlify.app

Results
Model	Accuracy	F1 (macro)	Parameters
MobileNetV2	84.74%	0.8306	2.27M
EfficientNet-B0	89.21%	0.8795	4.06M
Dataset: TrashNet (2,527 images).

Folder Structure
app/ — mobile web app (TensorFlow.js, runs the model in-browser)
notebooks/ — training and conversion notebooks
trained_models/ — trained Keras models
