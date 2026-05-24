# 💻 Laptop Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting laptop prices using Machine Learning regression techniques based on laptop specifications such as company, RAM, processor, storage, GPU, operating system, screen resolution, weight, and other hardware-related features.

The objective of this project is to build and compare multiple regression models to identify the best-performing approach for accurate laptop price prediction.

---

## 🎯 Objective

The main objective of this project is to:

- Predict laptop prices based on specifications
- Compare different regression models
- Analyze model performance using evaluation metrics
- Identify the most accurate regression model for price prediction

---

## 📂 Dataset Information

The dataset contains information about laptops and their specifications.

### Features Used

| Feature | Description |
|----------|-------------|
| Company | Laptop brand/company |
| TypeName | Type of laptop |
| Inches | Screen size |
| ScreenResolution | Display resolution |
| CPU | Processor details |
| RAM | Installed RAM |
| Memory | Storage configuration |
| GPU | Graphics card details |
| OpSys | Operating system |
| Weight | Laptop weight |
| Price | Target variable |

### Dataset Size
- **Total Records:** 1303
- **Features:** 11 input features + target variable

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Machine Learning Models Implemented

The following regression models were implemented and compared:

1. **Linear Regression**
2. **Ridge Regression**
3. **Lasso Regression**
4. **Elastic Net Regression**
5. **Polynomial Regression (Degree 2)**
6. **Decision Tree Regressor**
7. **Random Forest Regressor**

---

## 📊 Evaluation Metrics

The models were evaluated using:

- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**
- **5-Fold Cross Validation**

These metrics were used to compare model performance on validation and test datasets.

---

## 📈 Project Workflow

The project follows the following pipeline:

### 1. Data Collection
- Laptop dataset loaded using Pandas

### 2. Data Preprocessing
- Data cleaning
- Feature extraction
- Encoding categorical features
- Handling numerical transformations

### 3. Exploratory Data Analysis (EDA)
- Data visualization
- Correlation analysis
- Distribution analysis

### 4. Model Training
Multiple regression models were trained and tested.

### 5. Performance Evaluation
Models were compared using:
- MSE
- MAE
- R² Score
- Cross-validation results

### 6. Visualization
Performance comparison graphs and prediction analysis were generated.

---

## 📁 Project Structure

```text
LaptopPricePrediction/
│── laptop_data.csv
│── ML_Final_Project_(LAPTOP_PRICE_PREDICTION_).ipynb
│── README.md
│── requirements.txt
```

---

## 🚀 Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Anindya-Midhey/LaptopPricePrediction-ML.git
```

### Step 2: Navigate to Project Folder

```bash
cd LaptopPricePrediction-ML
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
ML_Final_Project_(LAPTOP_PRICE_PREDICTION_).ipynb
```

---

## 📌 Key Highlights

✅ Multiple regression models comparison

✅ Cross-validation for robust evaluation

✅ Feature engineering on laptop specifications

✅ Model performance visualization

✅ End-to-end machine learning pipeline

---

## 👨‍💻 Author

**Anindya Midhey**

---

## ⭐ If you found this project useful, consider giving it a star!
