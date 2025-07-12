# Obesity Prediction Using Machine Learning - Flask Web App

## Overview

This project implements a web application for predicting obesity levels using machine learning models. It provides functionalities including user registration/login, dataset upload, data preprocessing, model training, evaluation, and obesity prediction based on user inputs.

The backend is built with Flask, and machine learning models such as Logistic Regression, Decision Tree, Random Forest, Extra Trees, and AdaBoost are used for classification.

---

## Features

- User registration and login system backed by MySQL
- Upload obesity-related datasets via web interface
- Data preprocessing including handling categorical variables and outlier removal
- Train/test split with customizable test size
- Multiple ML model selection and evaluation with accuracy reporting
- Real-time obesity level prediction from user input features
- Visualization of uploaded data
- Clean and interactive web interface

---

## Getting Started

### Prerequisites

- Python 3.7+
- MySQL Server with a database named `obiseity` and table `obiseityusers`
- Required Python packages (see `requirements.txt`)

### Installing Dependencies

Use the provided `requirements.txt` to install dependencies:

```bash
pip install -r requirements.txt
