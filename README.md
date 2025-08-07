# 🏡 RealEstate Price Predictor using ML & EDA

This project is a machine learning-based solution to predict real estate prices based on key features such as location, area, number of bedrooms, and more. It covers the full pipeline — from exploratory data analysis (EDA) to model building and evaluation — using real-world housing data from Hyderabad and Mumbai.

---

## 📌 Key Features

- 📊 Performed detailed Exploratory Data Analysis (EDA) to understand data patterns and relationships.
- 🧹 Cleaned and processed 90,000+ property listings with Pandas and NumPy.
- 🧠 Built ML models including Linear Regression and Random Forest Regressor.
- 🔍 Feature selection and correlation analysis to improve model accuracy.
- 📈 Evaluated models using R² Score, Mean Squared Error (MSE), and visualization plots.

---

## 🛠️ Tech Stack

| Tool / Library       | Purpose                               |
|----------------------|----------------------------------------|
| Python               | Programming language                   |
| Pandas, NumPy        | Data wrangling and manipulation        |
| Matplotlib, Seaborn  | Data visualization                     |
| Scikit-learn         | Machine learning algorithms & metrics  |
| Jupyter Notebook     | Interactive development environment    |

---

## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ABHISHEKJULA07/RealEstate-Predictor-using-ML-EDA
   cd RealEstate-Predictor-using-ML-EDA
 ```bash
2. **Install the Required Packages**
Copy code
pip install -r requirements.txt
Run the Notebook


Copy code
jupyter notebook
Open and run: RealEstate_Predictor_EDA.ipynb

📁 Project Structure
csharp
Copy code
RealEstate‑Predictor‑using‑ML‑EDA/
├── data/                     # Dataset files
├── images/                   # Graphs & visualizations
├── RealEstate_Predictor_EDA.ipynb  # Main notebook
├── requirements.txt          # Required libraries
└── README.md                 # Project documentation
📈 Model Results
Best Model: Random Forest Regressor

R² Score: ~0.82

Top Influential Features: Location, Area (sqft), Bedrooms, Property Type

