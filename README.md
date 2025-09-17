

<p align="left">
<img alt="License" src="https://img.shields.io/badge/License-MIT-blue.svg">
<img alt="Python" src="https://img.shields.io/badge/Python-3.9%2B-blueviolet">
<img alt="Models" src="https://img.shields.io/badge/Models-Ensemble_ML_Methods-4285F4">
<img alt="Framework" src="https://img.shields.io/badge/Framework-Scikit--learn-orange">
<img alt="Framework" src="https://img.shields.io/badge/Visulisation-Matplotlib-green">
<img alt="RStudio" src="https://img.shields.io/badge/RStudio-4285F4?style=flat&logo=rstudio&logoColor=white">
</p>

# Predicting Phytoplankton Dynamics with Explainable AI

This project uses machine learning and explainable AI (XAI) to predict and understand the phytoplankton dynamics in the Falling Creek and Beaverdam Reservoirs in Virginia. By analyzing environmental variables collected at the sites, we uncover the hidden patterns driving phytoplanktons, offering insights for water quality management and ecological research. 

---

## 📁 Project Structure


### Step 1: Fetch the Data

To begin the analysis, you first need to get the dataset. You can do this by following steps below:

  - Run the R code from the GitHub Repository (https://github.com/abreefpilz/Reservoirs/blob/master/Scripts/Daily_avg_RS.R)

The script automatically fetches the required data packages directly from the EDI portal, processes the variables, and saves the final output as a .csv file.

Running this script will reproduce the FCR_BVR_Met_daily_obs_2019_2024.csv used for this project (uploaded here). 


### Step 2: Data Analysis and Visualization

Once the data is retreived/loaded, the next step is to perform an exploratory data analysis (EDA). 


  -  The chl-a_timeseries.ipynb notebook is provided for this purpose.

 This script process the phytoplankton (chlorophyll-a) data , visualize trends, and generate plots to understand the dataset's characteristics.

 ### Step 3: ML-XAI implemenation

The machine learning and explainable AI analyses are performed in two separate Jupyter Notebooks, with one dedicated to each reservoir as descibed below

  - Falling Creek Reservoir (FCR)



Contains the complete ML models and SHAP analyses with figures for the FCR.

  -  Beaverdam Reservoir (BVR)



Contains the complete ML models and SHAP analyses with figures for the BVR.

---

## Bathymetry Data Processing & Visualization

The bathyemtery figures for each reservoir are generated using the notebook below.



---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rohitshukla01/XAI_Manuscript_Analyses.git
cd XAI_Manuscript_Analyses
```

---

## ✅ Citation & Data Access

📑 If you use this code in a publication, cite this repository.

🌐 Visit EDI portal for direct data acquisition: https://portal.edirepository.org/nis/home.jsp










