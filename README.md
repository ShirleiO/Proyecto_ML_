# 💎 Diamond Price Prediction – Machine Learning Project

This project aims to predict diamond prices using machine learning techniques. It involves data preprocessing, model training, evaluation, and deployment, providing insights into the factors influencing diamond pricing.

---

## 📊 Dataset

The dataset contains various attributes of diamonds, including:

- **Carat**: Weight of the diamond
- **Cut**: Quality of the cut (e.g., Fair, Good, Very Good, Premium, Ideal)
- **Color**: Diamond color grading from D (best) to J (worst)
- **Clarity**: A measurement of how clear the diamond is
- **Depth**: Total depth percentage
- **Table**: Width of the top of the diamond relative to the widest point
- **Price**: Price in US dollars
- **Dimensions**: Length (x), width (y), and depth (z) in mm

---

## 🛠️ Data Preprocessing

- **Handling Missing Values**: Checked for and addressed any missing data.
- **Encoding Categorical Variables**: Converted categorical features like 'cut', 'color', and 'clarity' into numerical values using encoding techniques.
- **Feature Selection**: Selected relevant features that contribute significantly to the price prediction.
- **Data Splitting**: Divided the dataset into training and testing sets to evaluate model performance.

---

## 🤖 Model Training

Implemented and compared multiple regression models:

- **Linear Regression**
- **Random Forest Regressor**
- **Decision Tree Regressor**

Evaluated models based on metrics such as:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

---

## 📈 Results

The models were trained and tested, with performance metrics indicating the accuracy of price predictions. Visualizations such as scatter plots and residual plots were used to assess model fit and identify any patterns or anomalies.

---

## 📁 Project Structure

📁 Proyecto_ML_/ ├── diamantes.ipynb # Spanish version of the notebook ├── diamonds.ipynb # English version of the notebook ├── data/ │ └── diamonds.csv # Raw dataset file ├── models/ # Saved machine learning models ├── README.md # Project documentation └── requirements.txt # List of dependencies


---

## 🔮 Future Enhancements

- **Hyperparameter Tuning**: Optimize model parameters for better performance.
- **Cross-Validation**: Implement k-fold cross-validation to ensure model robustness.
- **Feature Engineering**: Create new features or transform existing ones to improve model accuracy.
- **Deployment**: Develop an API or web application to make predictions accessible to users.

---
---

## 📦 Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

Install the required packages using:

```bash
pip install -r requirements.txt

---

## 🛠️ Getting Started

# Clone the repo
git clone https://github.com/ShirleiO/Proyecto_ML_.git
cd Proyecto_ML_

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook

# Open diamantes.ipynb (Spanish) or diamonds.ipynb (English) to explore the full analysis and model training process.
