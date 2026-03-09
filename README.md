# Age and Gender Prediction Project

## Overview

This project focuses on predicting **age and gender** using deep learning techniques. The model is trained on image data and learns facial features to classify gender and estimate the age group of a person.

The implementation is done using **Python and Deep Learning libraries** inside a Jupyter Notebook.

## Project Objectives

* Detect facial features from images
* Predict gender (Male/Female)
* Estimate age group
* Build a deep learning model for classification

## Technologies Used

* Python
* Jupyter Notebook
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib

## Project Structure

```
Age-Gender-Prediction/
│
├── age_gender_revised.ipynb   # Main notebook for training and testing
├── dataset/                   # Dataset used for training
├── model/                     # Saved trained model
└── README.md                  # Project documentation
```

## Dataset

The dataset contains facial images labeled with:

* Age
* Gender

Images are used to train a CNN model for classification.

## How to Run the Project

### 1 Clone the Repository

```
git clone <your-repository-link>
cd Age-Gender-Prediction
```

### 2 Install Requirements

```
pip install numpy pandas matplotlib tensorflow opencv-python
```

### 3 Run the Notebook

```
jupyter notebook
```

Open:

```
age_gender_revised.ipynb
```

Run all the cells step by step.

## Model Workflow

1. Load dataset
2. Data preprocessing
3. Image normalization
4. Build CNN model
5. Train the model
6. Evaluate model performance
7. Predict age and gender

## Results

The trained deep learning model can successfully predict:

* Gender of a person
* Approximate age group

## Future Improvements

* Use larger datasets
* Improve model accuracy
* Deploy model as a web application
* Add real-time camera prediction

## Author

**Tejesh Yewale**
Computer Engineering Student | Data Science Enthusiast
