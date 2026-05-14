
# Cat vs Dog Image Classification using CNN

This repository demonstrates how to build, train, and evaluate a Convolutional Neural Network (CNN) in Python to classify images of cats and dogs. The project utilizes the popular Kaggle "Dogs vs Cats" dataset and is implemented in a Jupyter Notebook.

## Dataset

- **Source:** [Kaggle: Dogs vs Cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- **Description:**  
  The dataset contains a total of 25,000 labeled JPEG images:  
  - **Training:** 20,000 images (dogs and cats)  
  - **Testing:** 5,000 images (dogs and cats)  

## Project Workflow

The included notebook covers the following major steps:

1. **Environment Setup**
   - Installation and configuration for Kaggle datasets and Google Colab, including downloading the required dataset files.

2. **Data Preparation**
   - Unzipping and organizing images into appropriate training and testing directories.
   - Data augmentation and preprocessing using `ImageDataGenerator`.

3. **Model Building**
   - Construction of a sequential Convolutional Neural Network (CNN) using Keras (TensorFlow) layers like `Conv2D`, `MaxPooling2D`, `Flatten`, and `Dense`.
   - Compilation with an appropriate loss function and optimizer.

4. **Model Training**
   - Fitting the model to the training data and validating its performance on a split of the dataset.

5. **Evaluation**
   - Evaluating the model’s accuracy and loss on the test data.
   - Visualization of training/validation accuracy and loss graphs.

6. **Prediction**
   - Using the trained model to predict unseen images and evaluate the results.

## How To Run

1. Open the `Dog_Vs_Cat_Classification.ipynb` notebook in [Google Colab](https://colab.research.google.com/) or your preferred Jupyter environment.
2. Make sure you have your Kaggle API key (`kaggle.json`) and upload it as directed in the notebook.
3. Run each cell sequentially to:
   - Install dependencies
   - Download and extract the dataset
   - Prepare and preprocess data
   - Build, train, and evaluate the CNN model
4. Analyze the results at the end of the notebook.

## Dependencies

- Python 3.10+
- Keras
- TensorFlow
- matplotlib, numpy, pandas
- Kaggle API
- Google Colab (optional, but recommended for GPU support)

Install via pip if running locally:
```bash
pip install tensorflow keras matplotlib numpy pandas kaggle
```

## Results

- The notebook will show the training and validation accuracy and loss charts.
- Model accuracy and metrics for test data can be found at the end of the notebook.

## References

- [Kaggle: Dogs vs Cats Dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Keras Documentation](https://keras.io/)


---

> **Author:** [chrajashekar45](https://github.com/chrajashekar45)  
> For questions or suggestions, feel free to open an issue.
