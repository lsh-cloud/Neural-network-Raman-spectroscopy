# Classification of materials using Raman spectra and Deep Learning

In this project a neural network classification model is created to identify materials from their Raman spectra. The Raman spectra in this project belong to the crystals ReS2 and ReSe2, these crystals have a large number of non-degenerate vibrational modes, and as a results the Raman spectra have a number of features that could be identified by a classification model. The classification models were made using TensorFlow and Keras.

## Technical Details

Typically for classification of image (2d data) Conv2D is used in the model. Raman Spectra are 1d data and so Conv1D are used in this model similar to how Conv2D are used in an image classification model.

## Setup instructions

Note: The Raman spectra could not be included in this repository but the code, step-by-step instructions, results and graphs are all available. If wanted the user can download the repository and use their own data.

Clone the repository: git clone https://github.com/your-username/raman-classification.git


