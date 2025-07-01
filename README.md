# 🌧️ Rain Prediction using Machine Learning

This project aims to predict whether it will rain tomorrow using historical weather data from Australian weather stations. It leverages a machine learning pipeline that includes data cleaning, feature engineering, model training, and performance evaluation.

## 📁 Project Structure

```
Rain_Prediction/
│
├── Rain_Prediction.ipynb       # Main notebook with full ML pipeline
├── README.md                   # Project overview and setup guide
└── dataset/                    # Folder for input CSV file (not included)
```

## 📌 Problem Statement

Accurate rainfall prediction is crucial for sectors like agriculture, water management, and transportation. This project builds a supervised learning model to classify whether it will rain the next day (`RainTomorrow`) based on weather conditions from the current day.

## 🔍 Dataset

- **Source:** (https://github.com/amankharwal/Website-data/blob/master/weatherAUS.csv)
- **Description:** Daily weather observations from multiple Australian locations.
- **Target Variable:** `RainTomorrow` (`Yes` or `No`)

> ⚠️ The dataset is not included in this repository due to file size restrictions.  
> Please download it manually from the Kaggle link and place the CSV file inside a folder named `dataset/`.

## ⚙️ How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/Rain_Prediction.git
   cd Rain_Prediction
   ```

2. **Download the dataset** and place it in the `dataset/` directory.

3. **Open the notebook** in Jupyter or Google Colab:

   - On your local machine:
     ```bash
     jupyter notebook Rain_Prediction.ipynb
     ```
   - On [Google Colab](https://colab.research.google.com/):
     - Upload the notebook and dataset manually.

## 🧪 Machine Learning Pipeline

- Data Cleaning and Handling Missing Values  
- Exploratory Data Analysis (EDA)  
- Feature Engineering and Encoding  
- Train-Test Split  
- Model Training (e.g., Random Forest, Logistic Regression)  
- Model Evaluation using Accuracy, Precision, Recall, etc.

## 📊 Evaluation Metrics

The model performance is evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report
- ROC Curve

Plots and visual outputs are included in the notebook for clarity.

## 📷 Sample Visualizations

- Heatmap of missing values  
- Count plots and distributions for key features  
- Confusion matrix visualization  
- Feature importance ranking (for tree-based models)

## 🚀 Future Improvements

- Add hyperparameter tuning with GridSearchCV  
- Include model deployment using Streamlit or Flask  
- Integrate real-time weather API for live prediction  
- Experiment with ensemble and deep learning models

## 👤 Author

**Ashwani Kumar**  
📍 Berlin, Germany  
🎓 AI and Data Science Student

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).
