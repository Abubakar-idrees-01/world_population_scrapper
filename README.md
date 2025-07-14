## 🧪 Code Overview

This notebook performs population data analysis for the year 2025 using Python and Pandas. Here's a breakdown of each section:

### 1. 📥 Data Collection
- Uses `requests` and `pandas.read_html()` to scrape the population table from Worldometer.
- The first HTML table is extracted and stored as a DataFrame.

### 2. 🧹 Data Cleaning
- Drops unnecessary columns (like `'#'`).
- Converts columns such as **Population (2025)** and **Net Change** from strings to integers by removing commas and symbols.
- Ensures all numeric columns are in proper formats for analysis.

### 3. 📊 Data Visualization
- **Bar Chart:** Top 10 most populous countries in 2025.
- **Scatter Plot:** Fertility Rate vs. Median Age.
- **Correlation Heatmap:** Shows relationships between variables using Seaborn.

### 4. 📄 Output
- Displays clean DataFrame samples and visual charts.
- Optionally saves the data to a CSV using `df.to_csv()`.

### 💡 Libraries Used
- `pandas` for data manipulation
- `matplotlib.pyplot` and `seaborn` for visualization
- `requests` for HTTP access

---
