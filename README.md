## 🫀 Heart Disease Prediction Model

This project uses a machine learning model to predict the likelihood of heart disease based on patient health indicators. The model is built using a dataset containing various features like age, cholesterol levels, resting blood pressure, etc.

### 📂 Project Structure

* `Heart_Prediction.ipynb` - Jupyter Notebook containing data preprocessing, model training, and evaluation.
* `data.csv` - Dataset used to train and evaluate the model.

### 📊 Dataset Description

The dataset contains the following columns:

* `age`: Age of the patient
* `sex`: Gender (1 = male; 0 = female)
* `cp`: Chest pain type
* `trestbps`: Resting blood pressure
* `chol`: Serum cholesterol in mg/dl
* `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
* `restecg`: Resting electrocardiographic results
* `thalach`: Maximum heart rate achieved
* `exang`: Exercise-induced angina
* `oldpeak`: ST depression induced by exercise
* `slope`: Slope of the peak exercise ST segment
* `ca`: Number of major vessels (0–3) colored by fluoroscopy
* `thal`: Thalassemia status
* `target`: Presence of heart disease (1 = yes; 0 = no)

### 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn (Logistic Regression, train/test split, evaluation)
* Matplotlib & Seaborn (visualization)

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Kaviii8/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook Heart_Prediction.ipynb
   ```

### ✅ Results

The notebook includes:

* Data visualization
* Model training using Logistic Regression
* Accuracy score and confusion matrix evaluation

### 📌 Future Improvements

* Add more models (e.g., Random Forest, SVM)
* Improve data preprocessing
* Deploy as a web app using Flask or Streamlit

### 📄 License

This project is open-source and available under the [MIT License](LICENSE).
