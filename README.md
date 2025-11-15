# README
# WHAM
Whale and Harris Hawk Optimization based clustering and routing

# Project Overview
This repository contains Python code that can be executed in both Jupyter Notebook and Google Colab. This README provides clear instructions on how to access, run, and manage the notebook files in either environment.
# How to Run the Code
# Running the Code in Jupyter Notebook
# Prerequisites
Ensure the following are installed on the system:

Python 3.x
Jupyter Notebook or JupyterLab
Required Python libraries

#Install Jupyter Notebook
bash
pip install notebook

#Install Project Dependencies
bash
pip install -r requirements.txt

# Launch Jupyter Notebook
bash
jupyter notebook
This will open a web interface where you can navigate to and open the notebook file.

# Run the Notebook
•	Open the notebook file.
•	Press Shift + Enter to run each cell.

#Running the Code in Google Colab
Google Colab allows you to run the notebook without installing anything locally.
Open Directly from GitHub
1. Go to Google Colab
2. Click File → Open Notebook
3. Select the GitHub tab
4. Paste the GitHub repository URL
5. Choose the .ipynb notebook file to open
6. Upload the given WHAM dataset

# Uploading Files in Colab
python
from google.colab import files
uploaded = files.upload()

# Mount Google Drive (Optional)
python
from google.colab import drive
drive.mount('/content/drive')

In Google Colab:

python
!pip install -r requirements.txt


# File Structure
│── .ipynb
│── requirements.txt
│── data/
│   └── dataset.csv
│── src/
│   └── script.py
│── README.md

# Support
If you face any issues, feel free to open an issue in the GitHub repository.
