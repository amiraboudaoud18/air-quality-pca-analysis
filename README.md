# Air Quality Analysis with PCA

## 📖 Overview
This project applies Principal Component Analysis (PCA) to analyze and visualize air quality data collected in an Italian city over one year. PCA was used to reduce dimensionality, detect patterns, and better understand the relationships between environmental measurements and pollution levels.

## 🛠️ Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📚 Dataset
The dataset was obtained from the UCI Machine Learning Repository and contains hourly-averaged measurements of pollutant concentrations, sensor responses, and environmental parameters recorded between 2004 and 2005. 

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
3. Open the Jupyter Notebook (air_quality_pca_analysis.ipynb) and run the cells.

## 📊 Key Features
- **Data Cleaning:** Handled missing values and outliers.
- **Data Standardization:** Centered and scaled variables.
- **PCA Analysis:** Performed eigen decomposition, analyzed explained variance.
- **Visualization:** Plotted correlation circles, principal component scores, and cumulative variance plots.
- **Interpretation:** Identified pollutant contributions and environmental trends influencing air quality.


## 📈 Results
- First 5 principal components explain ~97% of the total data variance.
- PC1 captures pollutant emissions (CO, Benzene).
- PC2 reflects environmental effects (Temperature, Humidity).
- Insightful visualizations (correlation circles, PCA biplots).

## 📄 License
This project is licensed under the MIT License.

## ✨ Acknowledgments
- UCI Machine Learning Repository for the Air Quality Dataset.
- Guidance provided by Dr. Zahraa Mohsen (Supervisor).

