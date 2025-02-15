# YCT-529_PBPK_Modeling
This repository contains PK-Sim simulation files, pharmacokinetic data, and Python scripts for analyzing YCT-529, MCC placebo, and Atazanavir. Simulations were run across 16,000 individuals (four doses, four populations) with an additional 1,000 Atazanavir simulations. Includes data preprocessing, visualization, and dose-response analysis.

# **PBPK Model & Data Analysis for YCT-529 Pharmacokinetics**

## **Overview**
This repository contains the **PK-Sim project file (.pksim5)**, Python scripts, and Jupyter Notebook for **physiologically based pharmacokinetic (PBPK) modeling and analysis of YCT-529**, a non-hormonal male contraceptive. **PK-Sim** was used to simulate **16,000 pharmacokinetic profiles** across four demographic populations (Black Americans, East Asians, White Americans, and Europeans) and **four dosing regimens** (15 mg, 45 mg, 90 mg, 180 mg). Additionally, Atazanavir was simulated as a reference compound across 1,000 individuals.

Due to **file size limitations**, the dataset is stored externally. You can **download all simulation results from the Google Drive link** below:

🔗 **[Capstone Research Data - Google Drive](https://drive.google.com/drive/folders/1aNzhYjV4fwAKMfu8Sjh9Xx_S3eiyMBtl?usp=sharing)**  

## **Repository Contents**
- **`PBPK_data_analysis.ipynb`** → Jupyter Notebook for exploratory data analysis and visualization.
- **`pbpk_data_analysis.py`** → Python script version of the analysis notebook.
- **`YCT-529_Simulations.pksim5`** → **PK-Sim project file** containing the full PBPK model (requires PK-Sim to run).

## **Running the Analysis**

### **Option 1: Using the Provided Data**
1. **Download the dataset from the Google Drive link above** and extract it to the same directory as the Python script or Jupyter Notebook.
2. Open **`PBPK_data_analysis.ipynb`** in Jupyter Notebook or **`pbpk_data_analysis.py`** in a Python environment.
3. Run the script to generate figures, dose-response plots, and statistical analyses.

### **Option 2: Running Simulations in PK-Sim**
If you wish to **replicate or modify the PBPK model**, you must install **PK-Sim**:

🔗 **[PK-Sim Installation Guide](https://github.com/Open-Systems-Pharmacology/Suite)**  
🔗 **[PK-Sim GitHub Repository](https://github.com/Open-Systems-Pharmacology/PK-Sim)**  

1. Download and install **PK-Sim** (Windows/Linux only).
2. Open **`YCT-529_Simulations.pksim5`** in **PK-Sim**.
3. Modify parameters, run new simulations, and export the output CSV files.

### **Practice with Validated Models**
If you're new to **PK-Sim**, consider starting with the **OSP PBPK Model Library**, which contains validated drug models:

🔗 **[OSP PBPK Model Library](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library)**

## **System Requirements**
- **Python 3.8+** (for analysis scripts)
- **Jupyter Notebook** (for interactive analysis)
- **PK-Sim** (for running or modifying the PBPK model)

## **License**
This repository follows the **GPLv2 License**, aligning with **Open Systems Pharmacology** licensing standards.

For more information about the **Open Systems Pharmacology Suite**, visit:  
🔗 **[Open Systems Pharmacology Project](http://setup.open-systems-pharmacology.org)**
