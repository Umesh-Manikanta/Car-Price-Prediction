# 🚗 Car Price and Type Prediction System

This project involves predicting car prices (MSRP) and car types using machine learning models. We use algorithms like Random Forest for price prediction and K-Nearest Neighbors (KNN) and Logistic Regression for car type classification.

<!--![Car Prediction Image](https://via.placeholder.com/800x300.png?text=Car+Price+Prediction)  
*Image showcasing car price prediction.*-->

## Table of Contents

- [📖 Introduction](#Introduction)
- [💻 Technologies](#Technologies)
- [⚙️ Installation](#Installation)
- [🚀 Usage](#Usage)
- [🧠 Model Details](#model-details)
- [📊 Results](#results)
- [🤝 Contributing](#contributing)


## 📖 Introduction

In this project, we aim to build two models:
1. **Price Prediction Model**: Predict the `MSRP` (Manufacturer's Suggested Retail Price) of cars based on various features.
2. **Type Classification Model**: Classify cars into categories based on their attributes.

Key Features:
- **Random Forest** for regression (price prediction).
- **K-Nearest Neighbors (KNN)** and **Logistic Regression** for classification (vehicle type).
- **Data preprocessing** including handling missing values, encoding categorical features, and scaling.

## 💻 Technologies

The following technologies are used in this project:

- Python (version 3.x) 🐍
- Libraries: `scikit-learn` 📘, `pandas` 🐼, `numpy` 🔢, `matplotlib` 📊, `seaborn` 🎨
- Jupyter Notebook 📓 for interactive development

## 🚀 Usage

Once you have installed the dependencies, you can run the Jupyter notebooks to train and evaluate the models.



### Data Preprocessing

The dataset used in this project requires preprocessing:
- Handle missing values
- Encode categorical variables
- Scale numeric features

The preprocessing steps are outlined in the notebooks.

## 🧠 Model Details

### 1. Price Prediction Model
- **Algorithm**: Random Forest Regressor 🌲
- **Features**: Year, Engine HP, Engine Cylinders, Highway MPG, City MPG, etc.

### 2. Type Classification Model
- **Algorithms**: KNN 🧑‍🤝‍🧑, Logistic Regression 📈
- **Features**: Vehicle size, Vehicle style, Number of doors, Engine type, etc.

## 📊 Results

### Price Prediction:
- The **Random Forest** model achieved an RMSE (Root Mean Squared Error) of `XXX`.

### Type Classification:
- **K-Nearest Neighbors** achieved an accuracy of `YYY`.
- **Logistic Regression** achieved an accuracy of `ZZZ`.

### Visualization:

Matplotlib and Seaborns is used for Visualizing the models

## 🤝 Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss changes.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request
## ⚙️ Installation

To install the project and its dependencies:

1. Clone this repository:
    ```bash
    git clone https://github.com/Umesh-Manikanta/Car-Price-Prediction.git

