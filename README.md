# Predicting-the-Success-of-Bank-Telemarketing-for-Selling-Long-term-Deposits

This project reproduces the methodology from an academic paper to evaluate and compare **Logistic Regression(LR)** and **Decision Tree(DT)** classifiers for predicting the success of a marketing campaign using the UCI Bank Marketing Dataset.

This project aims to extend an existing research paper by:
- Tuning model parameters and applying SMOTE to improve performance
- Adding and evaluating additional classification models(Support Vector Machine, K-Nearest Neighbors, and Neural Networks)
- Testing and evaluating the performance of the original methodology(LR,DT) on different datasets


## 📁 Project Folder Structure

```
Predicting-the-Success-of-Bank-Telemarketing-for-Selling-Long-term-Deposits/
│
├── Data/
│   └── bank-additional.csv                # Dataset from the research paper 
│   └── online_shoppers_intention.csv      # Dataset for testing and evaluating the models  
│                                            from the research paper
│── Final Project Report/
│   └── Final Project Report.pdf           # Project Report
│
├── Models/
│   └── Midterm_Project_bank.ipynb         # Reproducing the models from the research paper
│   └── Final_Project_bank.ipynb           # Tuning model parameters and adding different models 
│   └── Final_Project_New_Dataset.ipynb    # Testing and evaluating the performance of the original
│                                            methodology(LR,DT) on different datasets
│         
├── Presentation/
│   └── Mid-term Project Presentation.pdf  # Mid term Project slide deck
│   └── Final Project Presentation.pdf     # Final Project slide deck
│
├── LICENSE                                # License file
└── README.md                              # Project documentation
```

## 📄 Research Paper

[Predicting the Success of Bank Telemarketing for Selling Long-term Deposits:
An Application of Machine Learning Algorithms]
(https://www.researchgate.net/publication/352755139_Predicting_the_Success_of_Bank_Telem[…]erm_Deposits_An_Application_of_Machine_Learning_Algorithms))


## 💿 Dataset
- `bank-additional.csv`: Used to reproduce the methodology described in the original research paper
- `online_shoppers_intention.csv`: Used to test and evaluate the models from the research paper on a different dataset


## 🙇 Requirements

Before running the code, make sure you have the following Python packages installed:
- bash
pip install pandas numpy scikit-learn matplotlib seaborn

# How to run
1. Clone this repository or download the files
2. Open the Jupiter or Python script containing the code:
   - Midterm_Project_bank.ipynb
   - Final_Project_bank.ipynb
   - Final_Project_New_Dataset.ipynb
3. Ensure that `bank-additional.csv` is located in the same directory when running the notebook for reproducing the original study
   
　　Use `online_shoppers_intention.csv` when running `Final_Project_New_Dataset.ipynb`

5. Run the entire notebook/scrip
6. You will see:
   - Model evaluations (accuracy, precision, recall, F1 score, AUC score)
   - Confusion matrices
   - Classification reports
   - ROC Curves 

## ✅ Model evaluation metrics 
Both models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- AUC Score
- ROC Curve 
- Confusion Matrix

## 🧑‍🏫 Link to our Presentation
Mid-term Presentation 
https://www.canva.com/design/DAG4ghcmglo/MC6POLH7WbcaAwWHJDstOQ/view?utm_content=DAG4ghcmglo&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h6486d06992

Final Presentation
https://www.canva.com/design/DAG7uJFJQAI/ClJJTQlCCHv_J1thnN5biw/edit?utm_content=DAG7uJFJQAI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
   
