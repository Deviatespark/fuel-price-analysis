# ⛽ Fuel Price Analysis in Spain with AutoViz and Matplotlib

This project analyzes fuel prices in Spain using a CSV dataset. It filters the data by province, cleans the numeric price values, generates automatic visualizations with **AutoViz**, and creates a histogram with **Matplotlib**, which is saved as a PNG file.

---

## 📂 Project Structure

```
fuel_price_analysis/
├── prix_carburants.csv                        # Raw data (CSV)
├── fuel_price_analysis.ipynb                  # Jupyter Notebook
├── price_distribution_MADRID.png              # Output plot
├── EN_fuel_price_analysis_Sergio_Galvez.docx  # Full report (English)
├── ES_fuel_price_analysis_Sergio_Galvez.docx  # Full report (Spanish)
├── autoviz_output/ (optional)                 # For saving AutoViz plots (if extended)
└── README.md                                  # This file
```

---

## 🚀 How to Run

1. Place your dataset in the project directory (named `prix_carburants.csv`).
2. Run the notebook:

```bash
jupyter notebook fuel_price_analysis.ipynb
```

3. The notebook will:
   - Filter the data for the province **MADRID**
   - Clean price columns (converts '1,529' to 1.529)
   - Generate an automatic EDA report using AutoViz
   - Save a histogram of fuel prices to `price_distribution_MADRID.png`

---

## 🧰 Technologies Used

- Python 3.x
- pandas
- matplotlib
- AutoViz
- Jupyter Notebook

---

## 📈 Output Example

The resulting histogram saved as `price_distribution_MADRID.png` shows the price distribution for gasoline and diesel in the selected province.

---

## 📄 Full Report

Detailed reports summarizing the methodology, data transformation, analysis, and results are available below:

- 📘 [Read the full report in English](report/EN_fuel_price_analysis_Sergio_Galvez.pdf)
- 📙 [Leer el informe completo en español](report/ES_fuel_price_analysis_Sergio_Galvez.pdf)

---

## ✍️ Author

Developed by **Sergio Gálvez Reguera**  
Created as part of a university assignment and adapted for public sharing and professional portfolio use.
