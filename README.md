Placement Prediction Notebook
This repository contains a Jupyter Notebook for analyzing and predicting student placement packages based on CGPA using machine learning techniques.

Project Overview

This notebook demonstrates a data science workflow for:

Loading and exploring a dataset of student placements

Visualizing data distributions and relationships

Preprocessing and scaling features

Building and evaluating regression and classification models to predict placement package outcomes from CGPA

Dataset

The dataset used (placement.csv) consists of 200 rows and 2 columns:

cgpa: Student's CGPA

package: Placement package offered (in unspecified units)

Features

Data exploration and visualization using pandas, matplotlib, and seaborn

Data preprocessing with scikit-learn's StandardScaler

Model building using scikit-learn (train/test split, regression and classification metrics)

Evaluation using metrics such as RMSE, MAE, R², accuracy, confusion matrix, and ROC-AUC

Requirements

Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

Install dependencies with:

bash
pip install pandas numpy matplotlib seaborn scikit-learn
Usage

Clone this repository.

Place the placement.csv file in the same directory as the notebook.

Open 23324003_Chetan-1.ipynb in Jupyter Notebook or JupyterLab.

Run the cells sequentially to reproduce the analysis and results.

File Structure

23324003_Chetan-1.ipynb: Main notebook containing all code and analysis

placement.csv: Dataset file (not included; add your own)

Results

The notebook provides visualizations of the data, model training, and evaluation metrics for predicting placement packages based on CGPA.

License

This project is for educational purposes.

Author

Chetan

Acknowledgements

scikit-learn for machine learning utilities

matplotlib and seaborn for data visualization
