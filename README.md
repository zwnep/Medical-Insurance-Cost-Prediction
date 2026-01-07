# Medical-Insurance-Cost-Prediction
The project in this file is a machine learning application that aims to predict medical insurance charges using individuals' personal health and demographic data.

# Medical Insurance Cost Prediction

This project is a machine learning analysis designed to predict individual medical insurance costs based on various personal attributes. By analyzing demographic and health-related data, the model aims to estimate healthcare expenses accurately.

## 📂 Dataset

The project uses the `expenses.csv` dataset, which includes the following features:
* **age:** Age of the primary beneficiary.
* **sex:** Insurance contractor gender (female, male).
* **bmi:** Body mass index.
* **children:** Number of children covered by health insurance.
* **smoker:** Smoking status (yes, no).
* **region:** The beneficiary's residential area in the US (northeast, southeast, southwest, northwest).
* **charges:** Individual medical costs billed by health insurance (Target Variable).

## 🛠 Technologies Used

* **Python 3.x**
* **Pandas & NumPy:** Data manipulation and numerical operations.
* **Matplotlib & Seaborn:** Data visualization and EDA.
* **Scikit-Learn:** Data preprocessing, model training, and evaluation.

## 🚀 Methodology

1.  **Exploratory Data Analysis (EDA):**
    * Analyzed data distribution and checked for missing values.
    * Visualized correlations (e.g., impact of smoking on charges).
    * Detected and visualized outliers in numerical features like BMI.

2.  **Data Preprocessing:**
    * Encoded categorical variables (Label Encoding).
    * Split data into training and testing sets.
    * Applied feature scaling using `StandardScaler`.

3.  **Modeling:**
    * Applied multiple regression algorithms:
        * Linear Regression
        * Ridge & Lasso Regression
        * Random Forest Regressor
        * Gradient Boosting Regressor
    * Implemented **Polynomial Features** to capture non-linear relationships in the data.

## 📊 Results

The models were evaluated using the $R^2$ score. The analysis showed that tree-based ensemble methods combined with polynomial features provided the best performance.

* **Best Model:** Gradient Boosting Regressor (with Polynomial Features)
* **Performance:** Achieved an $R^2$ score of approximately **0.87**.

## 💻 Installation & Usage

1.  Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/medical-insurance-prediction.git](https://github.com/yourusername/medical-insurance-prediction.git)
    ```
2.  Install the required packages:
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn
    ```
3.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook medical_analysis.ipynb
    ```

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
