# Data Visualization Project: Is Italy Warming Up?

### Description
This project was developed as part of the **Data Visualization** course within the MSc in Data Science program. It focuses on a deep-dive statistical analysis of the Italian Climate Record over a 123-year period (1901–2024), utilizing high-fidelity historical data from the World Bank. The analysis moves beyond anecdotal evidence to apply rigorous data visualization techniques, quantifying the "Heating Effect," seasonal shifts, and the changing frequency of extreme weather events in the Mediterranean region.

### Project Objectives
* **Assess Summer Trends:** Verify if recent summers are statistically breaking historical records and identify temperature regime shifts.
* **Analyze Seasonal Stability:** Investigate whether transitional seasons (Spring/Autumn) are losing their distinctiveness or simply shifting vertically in temperature.
* **Quantify Extreme Events:** Measure the increasing frequency and intensity of extreme heat events and the disappearance of extreme cold events over the last century.
* **European Comparison:** Compare Italy's median monthly temperatures with other European countries (France, Spain, Belgium) to highlight the differences between Mediterranean and Oceanic climates.

### Methodologies Used
The following analytical and visualization techniques were employed:
* **Data Extraction & Processing:** Automated data retrieval via API and temporal structuring for time-series consistency.
* **Smoothing Techniques:** Application of 10-year Moving Averages to reduce year-on-year volatility and reveal underlying climate signals.
* **Percentile Analysis:** Tracking of 90th (heat) and 10th (cold) percentiles to define and visualize extreme outliers over time.
* **Geospatial & Comparative Analysis:** Use of heatmaps and comparative curves to visualize thermal amplitudes across different latitudes.

### Technologies Used
* **Programming Language:** Python.
* **Data Manipulation:** Pandas and NumPy for efficient time-series handling and variable aggregation.
* **Visualization Libraries:** Matplotlib and Seaborn for generating static, high-quality charts (line charts, heatmaps, distribution plots).
* **Data Source:** World Bank Climate Knowledge Portal API.
