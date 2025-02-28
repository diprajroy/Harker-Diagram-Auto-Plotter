

# Harker Diagram Auto-Plotter 📊  
_Automated Geochemical Data Visualization_

## **Overview**
This Python script automates the generation of **Harker diagrams**, which are commonly used in geochemical analysis to understand the variation of major oxides in rock samples. It reads a **CSV dataset**, selects **Al₂O₃** as the reference oxide, and plots scatter diagrams against all other numeric columns with trend lines.

## **Key Features**
✅ **Automated Plotting** – Generates all Harker diagrams in one go  
✅ **Linear Regression Trend Line** – Adds a best-fit line with correlation coefficient (r-value)  
✅ **High-Resolution Output** – Saves plots as high-quality PNG images (1000 dpi)  
✅ **Custom Save Directory** – User-defined location for saving output plots  

## **Usage**
1️⃣ Ensure your CSV file contains an **"Al2O3"** column.  
2️⃣ Run the script and provide the file path.  
3️⃣ Choose a directory to save the generated plots.  
4️⃣ The script will generate **all possible Harker diagrams** and save them automatically.  



## **Example Output**
Each Harker diagram shows **Al₂O₃ vs. another oxide** with:
✔ Blue scatter points (data)  
✔ Red trend line (linear regression)  
✔ Correlation coefficient (r-value)  

This script is useful for **geochemists, petrologists, and researchers** working on provenance studies, magma differentiation, or sedimentary rock analysis.

 
