# CNN Image Classification on CIFAKE Dataset

This project demonstrates a CNN model trained to classify real vs. AI-generated images using the CIFAKE dataset. The model is trained using TensorFlow and exported into 3 deployment formats:

- SavedModel (for cloud/server)
- TFLite (for mobile)
- TFJS (for browser)

## Accuracy
Final test accuracy: 95%+

## Directory Structure
- `saved_model/`: TensorFlow SavedModel format
- `tflite/`: TFLite model and labels
- `tfjs_model/`: TensorFlow.js model for browser deployment
- `notebook.ipynb`: Full training notebook
