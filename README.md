

# Heart Disease Predictive System

![Heart](https://0701.static.prezi.com/preview/v2/4s2octd4klive3huvg3shp2tj76jc3sachvcdoaizecfr3dnitcq_3_0.png)

This project aims to predict the likelihood of heart disease using a machine learning model. It involves data preprocessing, model training, testing, and prediction. The model is trained on a dataset containing various features related to heart health.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

Heart disease is a critical health concern. This project utilizes a machine learning approach to predict the presence or absence of heart disease based on input features such as age, gender, blood pressure, cholesterol levels, and more.

## Installation

1. Clone this repository:

```bash
git clone https://github.com/ChetanChoudhary007/heart-disease-prediction.git
cd heart-disease-prediction
```

2. Install the required libraries using:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib
```

## Usage

1. Run the provided Python script to train and test the heart disease prediction model:

```bash
python heart_disease_prediction.ipynb
```

2. Follow the prompts to see the training accuracy and test the model's predictions.

## Data and Preprocessing

The dataset used for training and testing is stored in the `Heart_Disease_Prediction.csv` file. Categorical values like "Heart Disease" are encoded, and the data is standardized for better model performance.

## Model

The prediction model employed here is a logistic regression classifier, chosen for its simplicity and interpretability. Other classifiers like Support Vector Machines (SVM) could also be explored.

## Heart Disease Prediction System

The Heart Disease Prediction System is a comprehensive solution designed to predict the likelihood of heart disease based on individual health attributes. Here's an overview of the system's functionality:

1. **Data Collection and Preprocessing**: The system starts by loading a dataset containing various heart health attributes. Categorical data is encoded, and the dataset is standardized for consistent model performance.

2. **Model Training**: A logistic regression classifier is employed to train the prediction model. This involves using a training dataset to learn the relationships between input features and heart disease outcomes.

3. **Model Testing and Evaluation**: The trained model is tested using a separate testing dataset. Accuracy scores are calculated to measure the model's performance in predicting heart disease outcomes.

4. **User Input and Prediction**: The system prompts users to input their health attributes. The input data is preprocessed and standardized before being fed into the trained model. The system then predicts the likelihood of heart disease based on the provided information.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -am 'Add feature'`.
4. Push your changes to the branch: `git push origin feature-name`.
5. Open a pull request, explaining your changes and improvements.

## License


