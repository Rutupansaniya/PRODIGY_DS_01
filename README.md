# 🌍 Global Population Data Visualization

This project focuses on visualizing global population statistics using real-world data from the [World Bank](https://data.worldbank.org/indicator). It includes gender-based analysis and total population comparisons across countries, with a strong emphasis on data preprocessing and outlier handling to ensure accurate and meaningful insights.

## 📊 Visualizations

- **Grouped Bar Chart**: Male vs. Female population percentages by country
- **Separate Bar Charts**: Individual male and female population percentages
- **Total Population Chart**: Comparing country-wise population totals
- **Histogram**: Distribution of female population percentages across countries (2023)

## 🧹 Data Preprocessing

- Removed non-country entities and outliers from "Country Name"
- Handled missing values and invalid entries
- Focused on the most recent data available (2023)

## 📁 Dataset

- Source: [World Bank Gender and Population Indicators](https://data.worldbank.org/indicator)
- Indicators used:
  - `SP.POP.TOTL.FE.ZS`: Female population (% of total)
  - `SP.POP.TOTL.MA.ZS`: Male population (% of total)
  - `SP.POP.TOTL`: Total population

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**: 
  - `Pandas` for data handling and cleaning
  - `Matplotlib` for data visualization



