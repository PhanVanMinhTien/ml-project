# Machine Learning Project – Stroke Prediction

## 1. Course Information

- **Course Name:** Machine Learning  
- **Course Code:** CO3117  
- **Semester:** Semester 252 
- **Academic Year:** 2025 – 2026

---

## 2. Instructor

- **Instructor:** Dr. Truong Vinh Lan

---

## 3. Team Members

| Full Name | Student ID | Email |
|-----------|------------|-------|
| Phan Van Minh Tien | 2153888 |  |
| Le Quang Thanh  | 2252749 | thanh.leeq2252749@hcmut.edu.vn |
| To Dang Duc Tai | 2252725 |  |
| Nguyen Trong Minh Anh | 2252483 |  |
| Nguyen Thi Anh Thuy | 2252792 |  |

---

## 4. Project Objective

The objective of this project is to apply **traditional machine learning techniques** to build a model that predicts the likelihood of **stroke occurrence** based on patient health and demographic information.

The project follows a standard machine learning pipeline including:

### Exploratory Data Analysis (EDA)
- Descriptive statistics of the dataset
- Data visualization
- Detection of missing values and outliers
- Analysis of feature distributions

### Data Preprocessing
- Data cleaning
- Handling missing values
- Encoding categorical variables using **One-Hot Encoding**
- Feature scaling using **StandardScaler**
- Splitting the dataset into **training and testing sets**

### Dimensionality Reduction (Optional)
- Applying **Principal Component Analysis (PCA)** to reduce feature dimensionality while preserving most of the variance.

### Model Training
Training several machine learning models such as:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- k-Nearest Neighbors (k-NN)

### Model Evaluation
Evaluating model performance using:
- Accuracy
- Precision
- Recall
- F1-score

---

## 5. How to Run the Notebook

This project is fully optimized to run on **Google Colab**. Following the assignment requirements, there is no need to manually download datasets or mount personal Google Drive accounts. 

**Execution Steps:**
1. Open [Google Colab](https://colab.research.google.com/drive/1Hbt76cq9jZSi1GZKpvI7l1A8kiXIvlBE?usp=sharing).
2. In the top menu, navigate to **Runtime** > **Run all**.
3. The notebook will automatically fetch the stroke dataset from a public raw GitHub URL, install any missing dependencies, and execute the entire pipeline from EDA to Deep Learning evaluation without errors.

### 5.1 Required Libraries
The notebook utilizes standard Python libraries for data science and machine learning. Most are pre-installed on Google Colab.
* `pandas` & `numpy`: Data manipulation and numerical operations.
* `matplotlib`, `seaborn`, `missingno`: Data visualization and missing value matrix.
* `scikit-learn`: Preprocessing (StandardScaler, SimpleImputer, OneHotEncoder), PCA feature extraction, and Traditional ML models (Logistic Regression, Random Forest, SVM).
* `tensorflow` / `keras`: Building and training the Deep Learning (MLP) model.

---

## 6. Folder Structure

The repository is organized exactly according to the course guidelines to ensure a clean and reproducible workspace:

```text
StrokePrediction-ML/
│
├── notebooks/
│   └── ass1_stroke.ipynb     # Main Google Colab notebook containing the full pipeline
│
├── reports/
│   └── assignment_report.pdf     # The final comprehensive LaTeX-generated report
│
├── features/
│   ├── X_train_pca.npy           # Extracted PCA features (Train)
│   ├── X_test_pca.npy            # Extracted PCA features (Test)
│   ├── y_train.npy               # Target labels (Train)
│   └── y_test.npy                # Target labels (Test)
│
├── modules/                      # (Optional) Custom Python helper scripts
│
└── README.md                     # Project documentation
```
## 7. Link to report and Colab

1. Google Colab Notebook: [Google Colab](https://colab.research.google.com/drive/1Hbt76cq9jZSi1GZKpvI7l1A8kiXIvlBE?usp=sharing)
2. Link to report: [Report](https://github.com/PhanVanMinhTien/ml-project/blob/main/reports/report_btl_ML.pdf)
