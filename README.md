<img src="https://i.pinimg.com/originals/2d/41/ef/2d41ef4c38646cd6a053d7f12a010453.gif" alt="MasterHead" width="1000" height="500">

# Butterfly and Moth Species Identification using TensorFlow

## Overview
This project focuses on identifying 12 species of butterflies and moths using TensorFlow's pre-trained models like MobileNet and EfficientNet. The goal was to achieve a simple, yet highly accurate model with 100% accuracy in identifying these species. 

The simplicity of the model is intentional to ensure fast processing of data while maintaining accuracy. This project not only tests my skills in Python and TensorFlow deep learning but also serves as a foundation for future projects aimed at identifying various species of insects in Uganda. My inspiration for this project comes from my participation in the Tropical Biology Association, where I struggled to identify species due to a lack of reliable tools.

## Datasets

### Training Data
The training data is organized by species and can be found in the `training_data` folder. Each species has its own zip file containing images used for training the model. 

### Testing and Validation Data
Testing and validation images are provided in the zip files within the repository. You can also manually test the model using the images provided in the `ManualTesting` folder.

## Dataset Source
The dataset used for this project can be found on Kaggle: [Butterfly Images (100 species)](https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species).

## Models Used
- **MobileNet**: A lightweight, efficient deep learning model designed for mobile and embedded vision applications.
- **EfficientNet**: A more advanced model that balances accuracy and efficiency by scaling up the network width, depth, and resolution.

## Usage

### Packages needed
You would need the following packages installed in your virtual environment before using the notebook.
- **Numpy**
- **Pandas**
- **Tensorflow**
- **Matplotlib**
- **Os**

## Technical Skills Demonstrated

- **Image Processing**: Preprocessing images including resizing, normalization, and augmentation to improve model performance.
- **Convolutional Neural Networks (CNNs)**: Leveraging CNN architectures for feature extraction and classification of butterfly and moth species.
- **Model Optimization**: Fine-tuning pre-trained models (MobileNet, EfficientNet) to achieve high accuracy while maintaining efficiency.
- **Data Management**: Organizing large datasets for training and testing, including handling image datasets from external sources.
- **TensorFlow and Keras**: Utilizing TensorFlow and Keras for building, training, and deploying deep learning models.
- **Performance Evaluation**: Assessing model performance using metrics like accuracy and confusion matrix, and improving the model based on validation results.

## Current Status

The project has successfully achieved 100% accuracy in predicting the species of moths and butterflies using the EfficientNet pre-trained model. The next step is to develop a web application using Streamlit, allowing users to upload images and identify species directly through a user-friendly interface.

## Future Work
This project is a stepping stone towards building a more comprehensive application that can identify various insect species, particularly those found in Uganda. The future scope of this project includes:

- Expanding the dataset to include more species of butterflies, moths, and other insects.
- Developing a mobile application that can be used by biologists and enthusiasts in the field.
- Improving the model to handle larger datasets while maintaining high accuracy and efficiency.

## Contributing
Contributions are welcome! Please feel free to fork this repository and submit pull requests.
