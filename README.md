# Surface Temperature Dataset - Exploratory Data Analysis (EDA)

## Objective / Abstract
This project explores the **Surface Temperature Dataset** to identify key patterns, trends, and relationships. The primary objectives include:

- Understanding variations in surface temperature across different geographic and temporal dimensions.
- Investigating the impact of potential environmental factors on temperature changes.
- Identifying trends that can inform climate policies and environmental strategies.

By analyzing variables such as temperature readings, geographic information, and temporal data, actionable insights are provided to:

- Enhance climate research.
- Improve environmental forecasting models.
- Support decision-making in climate-related policies.

The ultimate goal is to contribute to global climate research and foster sustainable practices.

---

The dataset comprises 71 columns and 641 rows, representing details of surface temperature changes across countries from 1961 to 2022. Key columns include:

Column Name

Description

Country

Name of the country.

ISO3

ISO3 code for the country.

Indicator

Description of the temperature change measurement.

Unit

Measurement unit (Degree Celsius).

Source

Source of the data.

Sub-Region

Geographical grouping of the country.

Income Group

Classification based on income levels (e.g., Low, Middle, High).

Area (KM²)

Area of the country in square kilometers.

Density (KM²)

Population density of the country.

1961–2022 (Year Columns)

Annual temperature deviations in degrees Celsius for each year in the range.


---

## Questions Explored

1. **Temperature Distribution**: What is the distribution of surface temperatures? *(Histogram)*
2. **Geographic Trends**: How do temperatures vary across regions? *(Heatmap/Bar chart)*
3. **Seasonal Analysis**: What are the seasonal trends in temperature? *(Line plot)*
4. **Correlation Analysis**: Are there correlations between temperature and other variables? *(Heatmap/Scatter plot)*
5. **Anomalies Detection**: Are there outliers or anomalies in temperature data? *(Box plot)*

---

## Key Findings & Conclusion

1. **Temperature Distribution**:
   - [Highlight findings from temperature data, e.g., skewness or mean values.]

2. **Geographic Trends**:
   - [Summarize geographic observations, e.g., hotter regions or cold spots.]

3. **Seasonal Analysis**:
   - [Summarize findings on seasonal variations.]

4. **Correlation Analysis**:
   - [Highlight key relationships between variables.]

5. **Anomalies Detection**:
   - [Summarize insights about outliers and their significance.]

---

## Implications

This analysis provides actionable insights into surface temperature trends:

- **Policy Impact**: Findings can help shape climate policies targeting specific regions or periods.
- **Climate Models**: Improved accuracy in temperature forecasting models.
- **Public Awareness**: Insights into temperature trends can promote sustainable practices.

---

## Tools & Libraries

- **Python**: For data analysis and preprocessing.
- **Pandas, NumPy**: For data manipulation.
- **Matplotlib, Seaborn**: For creating visualizations.

---

## Resources

- **Dataset**: Surface Temperature Dataset (uploaded locally).
- **Analysis Framework**: ChatGPT.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/bilal1427/surface-temperature-eda.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis:
   ```bash
   python analyze.py
   ```

