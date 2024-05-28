# Machine Learning Model Trainer

## Overview
This project aims to simplify the machine learning workflow using PyCaret, an open-source, low-code machine learning library in Python. The project provides a user-friendly web application built with Streamlit, allowing users to upload their datasets, perform exploratory data analysis (EDA), and train machine learning models with ease.
---
## Objectives
1. Explore PyCaret functionality for data loading, EDA, model training, evaluation, and AutoML.
2. Develop a general machine learning package to automate data handling and model training.
3. Create an interactive web app using Streamlit for seamless user experience.

## Features
- **Data Loading**: Supports CSV and Excel file formats.
- **Exploratory Data Analysis (EDA)**: Includes various plots for data visualization.
- **Data Preprocessing**: Handles null values and encodes categorical data.
- **Model Training**: Allows users to choose models manually or use AutoML for model selection.
- **Model Evaluation**: Provides performance metrics for both classification and regression tasks.
- **User-Friendly Interface**: Streamlit web app for easy interaction.
---
## Installation
1. Clone the repository
2. Make sure you have streamlit downloaded, if not, on your console, run this command in your console: `!pip install streamlit`
3. This project also uses pandas, numpy, sklearn, matplotlib, and pycaret. Please make sure you have them all downloaded so you don't encounter any errors.
   - if you don't have them downloaded or want to check if you do, run this command in your console: `!pip install [library name]`

## Usage
1. Through your console, navigate to the project directory: `cd [prject dicrectory on your device]`
2. Run the Streamlit app through your console: `streamlit run Machine Learning Model Trainer.py`
3. Upload your dataset.
4. Perform EDA, preprocess data, and select the target variable.
5. Choose the model training method: Auto-Detect Best Model or select a model manually.
6. Train the model and evaluate its performance.
7. Explore the results.
---
## Contributors
- [Omar (Ven)](https://github.com/your-username)
- [ElectoPI](https://electropi.ai/) (For providing the opportunity to develop this project)
---
## License
This project is licensed under the CC0 License - see the [LICENSE](LICENSE) file for details.
