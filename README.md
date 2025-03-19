# 🏆 Super Smash Bros. Ultimate Data Analysis

## 📌 Project Overview
This project explores Super Smash Bros. Ultimate character statistics through data visualization and interactive analysis. Using Pandas, Matplotlib, NumPy, and Ipywidgets, I created visualizations to analyze character attributes like weight, speed, and attack range. The project was inspired by an Intro to Pandas lecture, where Pokémon stats were analyzed, but I applied the concepts to Super Smash Bros. instead.

## 🗂️ Dataset
- Source: Kaggle (Super Smash Bros. Ultimate character stats)
- Data Size: 78 rows × 5 columns (1.98 KB)
- Preprocessing: Cleaned and filtered the dataset in Excel before importing it into Python.

## 🏗️ Methods & Analysis
- Bar Chart & Slider: Interactive bar charts for character attributes with a slider for dynamic data filtering.
- Zoom & Attribute Selector: Bar chart with zoom-in/out functionality and a dropdown to select specific stats.
- Character Stats Lookup: Dropdown menu to select a character and view their individual stats.
- Color-Coded DataFrame: Applied a gradient color scheme to highlight stat differences.
  
## 🔍 Key Findings
- Certain attributes, like run speed and attack range, significantly impact competitive performance.
- Character tier rankings correlate with specific attribute distributions.
- Normalizing attributes improves data visualization clarity.
  
## 🚀 How to Run the Project

1. **Clone the repository**:  
   ```sh
    https://github.com/YourGitHubUsername/Super-Smash-Stats.git
   
2. **Install dependencies**:
This project uses the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- Ipywidgets
  
To install these dependencies, use:
```pip install -r requirements.txt  ```
3. **Running the Jupyter Notebook** :
Once you've cloned the repo and installed the dependencies, you can open and run the Jupyter Notebook.
- Navigate to the directory where the repo is cloned.
- Start Jupyter Notebook by running:
 ```sh
jupyter notebook
 ```
Open the Super-Smash-Analysis.ipynb file and run all cells.

## ⚙️ Technologies Used
Python · Pandas · NumPy · Matplotlib · Ipywidgets · Pandas Styler · Warnings

## 📌 Future Improvements
- Incorporate real match data to analyze win rates per character.
- Apply machine learning to predict character effectiveness in different matchups.
- Expand analysis to compare Super Smash Bros. Ultimate with past game versions.
