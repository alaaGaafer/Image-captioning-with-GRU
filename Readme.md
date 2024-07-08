
# Image Captioning with GRU

This project demonstrates image captioning using a GRU-based model, built on top of the VGG16 model for feature extraction. The script is designed to process images from a dataset, extract features, preprocess text captions, and train a GRU model for generating image captions.

## Project Overview

The project performs the following steps:
1. **Data Download and Extraction**: Downloads and extracts image and caption data.
2. **Feature Extraction**: Utilizes the VGG16 model to extract features from images.
3. **Caption Preprocessing**: Processes and tokenizes captions.
4. **Model Building and Training**: Constructs and trains a GRU-based model for image captioning.
5. **Data Generation**: Uses a custom data generator for training the model.


### Packages

- `numpy`
- `pandas`
- `tensorflow`
- `keras`
- `spacy`
- `PIL`
- `tqdm`



## Code Explanation

- **Data Download and Setup**: Downloads and sets up directories for data storage.
- **Feature Extraction**: Loads images, extracts features using VGG16, and stores them.
- **Caption Preprocessing**: Cleans and tokenizes text captions.
- **Model Building**: Constructs a GRU-based model for generating captions.
- **Data Generation**: Defines a custom data generator for model training.

## Results

The trained model can generate captions for images by providing features extracted from those images.


## Acknowledgements

- The VGG16 model and TensorFlow/Keras are used for feature extraction and model building.
- The dataset used is from Flickr8k and other image sources.

