# SONAR-Rock-vs-Mine-Prediction
# 🪨 SONAR Signal Classification using Logistic Regression

This project uses **Machine Learning** to classify SONAR signals as either **Rocks (R)** or **Mines (M)** based on 60 frequency-based features.
The model is built using the **Logistic Regression** algorithm from the `scikit-learn` library.

---

## 📘 Overview

Sonar systems detect objects underwater by sending and receiving sound waves. The dataset used in this project contains signals bounced off metal cylinders (mines) and rocks on the sea floor.
The goal is to train a machine learning model that can accurately identify whether a signal corresponds to a **mine** or a **rock**.

---

## 🧠 Key Steps

1. **Importing Dependencies**

   * Libraries used: `numpy`, `pandas`, `scikit-learn`.

2. **Data Loading and Exploration**

   * Loaded dataset: `Copy of sonar data.csv`.
   * Explored dataset shape, descriptive statistics, and label distribution.
   * Label meaning:

     * `M` → Mine
     * `R` → Rock

3. **Data Preprocessing**

   * Separated features (`X`) and labels (`Y`).
   * Split data into **training (90%)** and **testing (10%)** sets with stratification to maintain class balance.

4. **Model Training**

   * Algorithm: **Logistic Regression**.
   * Trained on the training dataset using scikit-learn’s `LogisticRegression()`.

5. **Model Evaluation**

   * Evaluated model on both training and test datasets using **accuracy score**.
   * Example accuracies:

     * Training Accuracy ≈ 83%
     * Test Accuracy ≈ 76% (varies depending on random state)

6. **Prediction System**

   * Accepts a new sonar reading (60 features) as input.
   * Outputs whether the object is a **Mine** or a **Rock**.

---

## 🧩 Dataset Information

* **Source:** UCI Machine Learning Repository – Sonar Dataset
* **Features:** 60 continuous attributes representing energy levels at different sonar frequencies.
* **Labels:**

  * `M` — Mine
  * `R` — Rock

---

## ⚙️ Technologies Used

* **Language:** Python
* **Libraries:**

  * `numpy`
  * `pandas`
  * `scikit-learn`
  * `matplotlib` *(optional for visualization)*

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/SONAR-Classification.git
   cd SONAR-Classification
   ```

2. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn
   ```

3. Open the notebook:

   ```bash
   jupyter notebook SONAR.ipynb
   ```

4. Run all cells sequentially to train and test the model.

---

## 📊 Results

| Dataset  | Accuracy |
| -------- | -------- |
| Training | ~83%     |
| Testing  | ~76%     |

---

## 🧾 Future Improvements

* Try advanced models like **SVM**, **Random Forest**, or **Neural Networks**.
* Perform **feature scaling** or **dimensionality reduction (PCA)**.
* Use **cross-validation** for more robust accuracy estimation.

---

## 👩‍💻 Author

**Shristi Singh**
📧 [wellallis057@gmail.com](mailto:wellallis057@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/shristisingh1312) | [GitHub](https://github.com/shristi13star)
