# internship_BVM
→ Titanic Dataset Prediction - ML Algorithms from Scratch

This project presents two popular supervised machine learning algorithms implemented from scratch using Python:

→ Naive Bayes

→ K-Nearest Neighbours (KNN)

These models were tested on the Titanic dataset to predict passenger survival.

---

→ Technologies Used

• Python 3.5+  
• NumPy  
• Pandas  
• Matplotlib

---

→ Model Results

| Model         | Accuracy |
|---------------|----------|
| Naive Bayes   | 81.00%   |
| KNN (k=5)     | 73.74%   |

Both algorithms were evaluated on a validation set (80-20 split). Naive Bayes showed better performance on this dataset.

---

→ Project Structure

• `titanic_classification.ipynb` → Full notebook with preprocessing, implementation, evaluation, and visualizations  
• `train.csv` / `test.csv` → Datasets used  
• `Finalsubmission.csv` → Final KNN-based predictions in Kaggle format  

---

→ Key Highlights

• No ML libraries like scikit-learn used  
• All logic (distance calculation, probability, etc.) implemented manually  
• Data cleaning: missing values handled, categorical encoding done  
• Visualizations: class-wise survival, confusion matrices, accuracy bars  

---

→ How to Run the Project

1. Clone the repository or download the files.  
2. Open `titanic_classifier.ipynb` in Jupyter Notebook.  
3. Run all cells in sequence.  
4. Try changing the value of `k` in the KNN function to observe variations.


