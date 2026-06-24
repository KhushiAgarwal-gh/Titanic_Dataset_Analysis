# 🚢 Titanic Data Analysis & Visualization

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using **Python, Pandas, Matplotlib, and Seaborn**. The objective is to clean the data, analyze passenger information, create meaningful visualizations, and derive insights from the dataset.

The project demonstrates essential data analysis skills such as:

* Data cleaning and preprocessing
* Handling missing values
* Data visualization
* Correlation analysis
* Storytelling with data

---

## 📂 Dataset

**Dataset:** Titanic Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (`Pclass`)
* Name
* Sex
* Age
* Number of Siblings/Spouses (`SibSp`)
* Number of Parents/Children (`Parch`)
* Ticket Fare (`Fare`)
* Embarked Port (`Embarked`)
* Survival Status (`Survived`)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📊 Visualizations Created

1. Survival Distribution
2. Gender Distribution
3. Age Distribution
4. Correlation Heatmap
5. Fare Distribution
6. Survival by Gender
7. Pairplot for Feature Relationships

All visualizations are saved as **PNG files**.

---

## 🧹 Data Cleaning Steps

* Checked for missing values.
* Filled missing values in the `Age` column using the median.
* Filled missing values in the `Embarked` column using the mode.
* Removed unnecessary columns with excessive missing values.
* Removed duplicate records.

---

## 🔍 Key Insights

* Most passengers did not survive the disaster.
* Female passengers had a significantly higher survival rate than male passengers.
* Most passengers were between 20 and 40 years old.
* First-class passengers paid higher fares and had better chances of survival.
* Fare and passenger class show a strong relationship.
* Age does not have a strong correlation with most other features.

---

## 📁 Project Structure

```text
Titanic-Data-Analysis/
│
├── Titanic_Data_Analysis.ipynb
├── Titanic-Dataset.csv
├── charts/
│   ├── chart1_survival_distribution.png
│   ├── chart2_gender_distribution.png
│   ├── chart3_age_distribution.png
│   ├── chart4_correlation_heatmap.png
│   ├── chart5_fare_distribution.png
│   ├── chart6_survival_gender.png
│   └── chart7_pairplot.png
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Titanic-Data-Analysis.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Titanic_Data_Analysis.ipynb` and run all cells.

---

## 📈 Future Improvements

* Build a machine learning model to predict passenger survival.
* Create an interactive dashboard using Plotly or Streamlit.
* Perform feature engineering and advanced statistical analysis.

---

## ⭐ Conclusion

This project demonstrates the complete workflow of a beginner-friendly data analytics project, including data preprocessing, visualization, and extracting meaningful insights from real-world data.
