# Antibiotic Resistance Modeling Project

This project explores the relationship between antibiotic resistance rates and factors such as antibiotic use in livestock, dietary patterns, and public health indicators across multiple countries.

## 📂 Project Structure

antibiotic_resistance_project/ ├── data/ │ ├── raw/ # Original uncleaned data │ ├── processed/ # Cleaned data used for modeling ├── notebooks/ │ ├── 01_exploration.ipynb # Data exploration and EDA │ ├── 02_model_building.ipynb # Model training and evaluation ├── scripts/ │ ├── clean_data.py # Data cleaning functions ├── outputs/ │ ├── figures/ # Scatterplots, feature importance plots │ ├── models/ # Trained model files (.pkl) ├── report/ │ ├── final_report.ipynb # Final report ├── README.md # Project overview (this file) ├── requirements.txt # List of required Python packages


## 📦 Requirements

Make sure you have Python 3.10+ installed.  
(🚨 Note: Project originally tested with Python 3.13.)

To set up your environment:

```bash
# 1. Create virtual environment
python3 -m venv venv-ar

# 2. Activate the environment
# Mac/Linux
source venv-ar/bin/activate
# Windows (cmd)
venv-ar\Scripts\activate.bat
# Windows (PowerShell)
venv-ar\Scripts\Activate.ps1

# 3. Install required packages
pip install -r requirements.txt
