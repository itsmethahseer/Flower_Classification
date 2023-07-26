# Flower_Classification

## Overview

This project focuses on Flower Classification using TensorFlow and OpenCV. Python libraries are utilized for visualization, and the Computer Vision package is installed for image-related tasks. TensorFlow is employed for the core machine learning part, and PIL (Python Imaging Library) is used for image analysis.

The dataset used in this project contains various types of flower images, including roses, daisies, dandelions, etc. The data is sourced from Google's website and is converted into OpenCV objects for further processing.

Dataset Source: [Flower Photos](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)

## Installation

To run this project, you need to install the required libraries:

```bash
pip install tensorflow opencv-python pillow
```

## Project Structure

The project includes the following files and directories:


- `notebooks/`: Jupyter notebooks that demonstrate the step-by-step process of flower classification. Notebooks cover data preprocessing, image visualization, and model training.

- `Flower_Classification.ipynb`: Python script with the main code for flower classification using Convolutional Neural Networks (CNN).

## Usage

To perform flower classification using TensorFlow and OpenCV, follow these steps:

1. Clone the repository to your local machine.

2. Install the required libraries.

3. Run the `Flower_Classification.ipynb` script to preprocess the data, train the CNN model, and perform flower classification.

## Performance and Data Augmentation

During testing, the model achieves approximately 65% accuracy, indicating potential overfitting. To address this issue, Data Augmentation techniques are employed, including transformations such as RandomZoom, RandomFlip, RandomContrast, etc. These augmentations help improve accuracy and generalization.

## Project Author

This project was developed by Muhammed Thahseer CK, a self-taught data scientist passionate about exploring the field of data science.

## Acknowledgments

Special thanks to Google for providing the flower dataset and the TensorFlow team for their excellent machine learning library.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Conclusion

Explore the exciting world of flower classification using Convolutional Neural Networks, TensorFlow, and OpenCV. The notebooks offer valuable insights into the preprocessing techniques and data augmentation to improve model performance.

Happy classifying and data science exploration!
