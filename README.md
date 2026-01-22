# Water Potability Prediction Using Machine Learning

This project focuses on predicting whether water is safe for drinking based on its physicochemical properties using machine learning classification techniques.

## Problem Statement
Access to safe drinking water is a critical public health concern. The goal of this project is to build and compare machine learning models that can classify water samples as potable or non-potable based on measured water quality parameters.

## Dataset
- **Source:** Kaggle – Water Potability Dataset  
- **Link:** https://www.kaggle.com/datasets/adityakadiwal/water-potability
- **Description:**  
  The dataset contains water quality metrics such as pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity, along with a binary target variable indicating potability.

> Note: The dataset is not included in this repository. Please download it directly from Kaggle using the link above.

## Approach
1. Data loading and initial exploration  
2. Handling missing values using statistical imputation  
3. Feature scaling where required  
4. Training and evaluation of multiple classification models  
5. Performance comparison across models  

## Machine Learning Models Used
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  

## Evaluation
Model performance was evaluated using classification metrics such as accuracy and confusion matrix analysis. The results demonstrate how different models perform on real-world environmental data and highlight their strengths and limitations.

## Tools and Technologies
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab  

## Project Structure
```bash
water-potability-prediction/
├── notebooks/
│ └── water_potability.ipynb
├── data/
│ └── README.md
├── requirements.txt
├── .gitignore
└── README.md
```

## How to Run
1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from Kaggle  
4. Open and run the notebook in Jupyter Notebook or Google Colab  

## Limitations
- Mean imputation may reduce feature variance  
- Accuracy alone may not fully capture real-world risk, especially for false negative predictions  
- Further tuning and additional evaluation metrics could improve model reliability  

## Program Context
This project was completed as part of the **IBM SkillsBuild – Mastering Data with Machine Learning** program in collaboration with **CSRBOX**.

## License
This project is licensed under the MIT License.



