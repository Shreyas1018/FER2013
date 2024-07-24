# FER 2013 Sentiment Analysis
### Introduction
This repository contains a Python implementation of a ResNet model for sentiment analysis on the FER 2013 dataset. The goal is to classify facial expressions into seven categories: 
- angry-
- disgusted
- fearful
- happy
- sad
- surprised
- neutral.

### Dependencies
- Python (>=3.6)
- TensorFlow/Keras
- OpenCV
- NumPy
- seaborn
- pickle
## Dataset
About Dataset
The data consists of 48x48 pixel grayscale images of faces. 
The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

### Model Architecture
The model is based on a ResNet 101 architecture, chosen for its ability to handle complex image patterns and avoid the vanishing gradient problem.

### Training
The training process involves:

- Data Preprocessing: Images are normalized and augmented.
- Model Compilation: The ResNet model is compiled with an appropriate optimizer (e.g., Adam) and loss function (e.g., categorical cross-entropy).
- Model Training: The model is trained on the training set using batch training with early stopping and model checkpoints.
### Results
The trained model is evaluated on the validation set to assess its performance.<br>
The model acheived:
- Accuracy: 65%
- loss: 1.009 <br>
On training dataset.

## Contributions
Contributions are welcome! Feel free to open issues or pull requests for bug fixes, feature enhancements, or new ideas.
