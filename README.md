
# ROCS Individual Analysis – University of York

This repository contains the Jupyter notebook submission for the ROCS (Research, Organisation, and Critical Skills) postgraduate module at the University of York. The analysis focuses on examining mobile app usage patterns across countries, with a specific case study on Instagram.

## 📊 Objective

To investigate whether there are measurable differences in the popularity of mobile applications—specifically Instagram—between Least Developed Countries (LDCs) and non-LDCs. The analysis involves statistical exploration and data visualization.

## 📁 Files

- `rocs_individiual_analysis.ipynb`: The main Jupyter Notebook containing all the code, plots, and statistical summaries.

## 📌 Key Components

- **Data Handling**: 
  - Mounts Google Drive to access the CSV dataset.
  - Loads a mobile app ranking dataset into a Pandas DataFrame.
  
- **Exploratory Data Analysis (EDA)**:
  - Filters data to focus on the Instagram application.
  - Computes average rank of Instagram usage per country.
  - Groups data by LDC status.
  
- **Visualization**:
  - Boxplot comparing Instagram's average rank between LDC and non-LDC countries.
  
- **Statistics**:
  - Descriptive statistics (mean, std, min, max) of Instagram's rank in both groups.

## 🧰 Dependencies

The notebook requires the following Python packages:

```bash
pandas
matplotlib
seaborn
google.colab (for drive access)
```

These are typically pre-installed in Google Colab.

## 🏫 Academic Context

This analysis was completed as part of the ROCS (Research, Organisation, and Critical Skills) module at the University of York. The module is designed to build students' ability to critically engage with data, organize research projects, and communicate findings effectively.

## 🔒 Note

This notebook is intended for academic assessment and demonstration purposes. Please do not reuse the content without appropriate attribution or in violation of academic integrity policies.
