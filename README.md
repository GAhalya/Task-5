## Titanic Dataset - Exploratory Data Analysis

## Dataset source
Dataset downloaded from Kaggle (Titanic survival prediction)

## 1. Data Import & Setup

- Extracted files from ZIP
- Uploaded CSV into Google Colab
- Created DataFrame using Pandas

## 2. Operations performed on dataset

- Checked information
- description of data
- Value counts for a column

## 3. Visualizations

- **Pairplot**: plotting amongst dataset columns
  
  **Observation:** Each column is plotted against the others for pattern recognition.
  
- **Heatmap:** correlation
  
  **Observation:** Observation: Survival has a positive correlation with Fare and negative correlation with Passenger Class
  
- **Histogram**:Fare Distribution

- **Boxplot**:Fare vs Survival

- **Scatterplot:** Age vs Fare by Survival
  
  **Observation** :
    - Death ratio is lower for age group 60–80
    - Higher fare passengers had better survival chances

## summary :

EDA included visualizations like pairplots, heatmaps, histograms, boxplots, and scatterplots. Survival showed a positive correlation with fare and a negative correlation with passenger class, indicating higher-class passengers had better chances. Overall, higher fares, higher class, and certain age groups were linked to increased survival rates.
