# 🏡 California Housing Price Prediction using Linear Regression

## 📌 Project Overview

This project was developed as part of an **Artificial Intelligence & Machine Learning Internship Task**. The objective was to build and evaluate a **Linear Regression Model** capable of predicting California house prices based on housing and demographic features.

The project demonstrates the complete Machine Learning workflow, including data loading, exploratory data analysis (EDA), model training, evaluation, visualization, and model deployment preparation.

---

## 🎯 Objective

To develop a machine learning model that predicts median house prices in California using the California Housing Dataset and evaluate its performance using standard regression metrics.

---

## 📂 Dataset

The project uses the **California Housing Dataset** available in the Scikit-Learn library.

### Features

| Feature | Description |
|----------|------------|
| MedInc | Median Income |
| HouseAge | Median House Age |
| AveRooms | Average Number of Rooms |
| AveBedrms | Average Number of Bedrooms |
| Population | Population in the Block |
| AveOccup | Average Occupancy |
| Latitude | Latitude Coordinate |
| Longitude | Longitude Coordinate |

### Target Variable

- **MedHouseVal** → Median House Value

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading
- Loaded California Housing Dataset using Scikit-Learn.

### 2. Exploratory Data Analysis (EDA)
- Dataset inspection
- Statistical summary
- Missing value analysis
- Correlation analysis
- Data visualization

### 3. Data Preprocessing
- Feature selection
- Train-test split

### 4. Model Training
- Linear Regression Model
- Training on 80% dataset

### 5. Model Evaluation
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 6. Visualization
- Correlation Heatmap
- Feature Distribution Histograms
- Actual vs Predicted Plot
- Residual Distribution Plot

### 7. Model Saving
- Saved trained model using Joblib

---

## 📈 Evaluation Metrics

The model performance was evaluated using:

### Mean Absolute Error (MAE)
Measures average prediction error.

### Root Mean Squared Error (RMSE)
Measures prediction accuracy while penalizing larger errors.

### R² Score
Indicates how well the model explains variance in the target variable.

Typical results achieved:

| Metric | Value |
|----------|--------|
| MAE | ~0.53 |
| RMSE | ~0.74 |
| R² Score | ~0.57 |

> Note: Results may vary slightly depending on train-test split and environment.

---

## 📷 Visualizations Included

- Histogram Analysis
- Correlation Heatmap
- House Price Distribution
- Income vs House Price Scatter Plot
- Actual vs Predicted Comparison
- Residual Error Distribution

---

## 📁 Project Structure

```text
California-Housing-Linear-Regression/
│
├── task1_ml_linear_regression.ipynb
├── Linear_Regression_Project_Report.docx
├── linear_regression_model.pkl
├── app.py
├── requirements.txt
└── README.md
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/California-Housing-Linear-Regression.git
```

Move into project directory:

```bash
cd California-Housing-Linear-Regression
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Running the Project

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
task1_ml_linear_regression.ipynb
```

Run all cells sequentially.

---

## 💾 Saved Model

The trained model is saved as:

```text
linear_regression_model.pkl
```

Load model:

```python
import joblib

model = joblib.load("linear_regression_model.pkl")
```

---

## 🔮 Predict New House Prices

Run:

```bash
python app.py
```

Enter housing details when prompted and receive a predicted house price.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Supervised Machine Learning
- Linear Regression
- Exploratory Data Analysis (EDA)
- Data Visualization
- Model Evaluation Techniques
- Machine Learning Workflow
- Model Serialization using Joblib

---

## 🔮 Future Enhancements

- Random Forest Regression
- XGBoost Regression
- Hyperparameter Tuning
- Feature Engineering
- Web-based Prediction Interface
- Model Deployment using Flask/FastAPI

---

## 👨‍💻 Author

**Divyakumar Jadhav**

Computer Engineering Student | AI & ML Enthusiast | Full-Stack Developer

LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

GitHub: https://github.com/your-github-username

---

## 📜 License

This project is created for educational and internship learning purposes.
