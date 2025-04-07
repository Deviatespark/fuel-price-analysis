# ⛽ Fuel Price Analysis in Spain with AutoViz and Matplotlib

This project analyzes fuel prices in Spain using a CSV dataset. It filters the data by province, cleans the numeric price values, generates automatic visualizations with **AutoViz**, and creates a histogram with **Matplotlib**, which is saved as a PNG file.

---

## 📂 Project Structure

```
fuel_price_analysis/
├── prix_carburants.csv            # Raw data (CSV)
├── fuel_price_analysis.ipynb      # Python script
├── price_distribution_MADRID.png  # Output plot
├── autoviz_output/ (optional)     # For saving AutoViz plots (if extended)
└── README.md                      # This file
```

---

## 🚀 How to Run

1. Place your dataset in the project directory (named `prix_carburants.csv`).
2. Run the script:

```bash
jupyter notebook fuel_price_analysis.ipynb
```

3. The script will:
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

---

## 📈 Output Example

The resulting histogram saved as `price_distribution_MADRID.png` shows the price distribution for gasoline and diesel in the selected province.

---

## ✍️ Author

Created as part of a university assignment and adapted for public sharing.
