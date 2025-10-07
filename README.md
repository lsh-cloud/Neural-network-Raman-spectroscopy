# Classification of crystals using Raman spectra and Deep Learning

In this project a neural network classification model is created to identify materials from their Raman spectra. The Raman spectra in this project belong to the crystals **ReS<sub>2</sub>** and **ReSe<sub>2</sub>**, these crystals have a large number of non-degenerate vibrational modes, and as a results the Raman spectra have a number of features that could be identified by a classification model. 

The classification model was made using **TensorFlow** and **Keras**.

## Technical Details

Typically for classification of images (2D data) **Conv2D** is used in the model. Raman Spectra are 1D data and as a result **Conv1D** are used in this model similar to how **Conv2D** are used in an image classification model.

## Setup instructions

>Note: The Raman spectra could not be included in this repository, but the code, step-by-step instructions, results and visualisation are all available. If wanted the user can download the repository and use their own data.

Clone the repository: git clone https://github.com/your-username/raman-classification.git


