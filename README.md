# Youth Unemployment Analysis

An advanced data science project analyzing global youth unemployment rates across 181 countries.  
The project applies **data cleaning, exploratory data analysis (EDA), clustering, outlier detection, classification modeling, and visualization** to uncover trends and insights.  
Interactive maps and machine learning models make this project unique and suitable for showcasing data science skills.

## Table of Contents
1. [Dataset](#dataset)
2. [Features](#features)
3. [Technologies](#technologies)
4. [Analysis Workflow](#analysis-workflow)
5. [Results](#results)
6. [How to Run](#how-to-run)
7. [Project Structure](#project-structure)
8. [Future Improvements](#future-improvements)
9. [License](#license)

## Dataset
- **Source:** Youth Unemployment dataset (181 countries).  
- **Columns:**  
  - Rank → Ranking of countries by unemployment rate  
  - Country → Country name  
  - Unemployment → Youth unemployment rate (%)  

## Features
- Clean and preprocess unemployment data
- Continent mapping with `country_converter`
- Exploratory Data Analysis with advanced visualizations
- Clustering countries using **K-Means**
- Outlier detection with **Isolation Forest**
- Classification of countries into **Low / Medium / High unemployment risk**
- Interactive world map visualization (Plotly choropleth)
- Models saved for reuse (`joblib`)

## Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Data Visualization: Matplotlib, Seaborn, Plotly
- Machine Learning: KMeans, Random Forest, Isolation Forest
- Country Mapping: country_converter

## Analysis Workflow
1. Load and clean the dataset
2. Map countries to continents
3. Perform EDA (histograms, boxplots, top countries, etc.)
4. Feature engineering (categories, log transform, one-hot encoding)
5. Clustering analysis with PCA visualization
6. Outlier detection
7. Classification model for unemployment categories
8. Build interactive choropleth map
9. Save models & results

## Results
- Countries with the **highest youth unemployment** include French Polynesia, Kosovo, and South Africa.
- Africa and the Americas show **higher median unemployment** compared to Europe and Asia.
- Clustering grouped countries into distinct unemployment risk levels.
- Outlier detection revealed extreme unemployment cases (>50%).

👉 See the interactive choropleth map in `youth_unemployment_choropleth.html`

## Future Improvements
- Add time-series forecasting if temporal unemployment data becomes available
- Build a Streamlit dashboard for interactive analysis
- Incorporate socio-economic indicators (GDP, education) for richer modeling

## License
This project is licensed under the MIT License - see the LICENSE file for details.
