# Supervised Classification of Vehicle Shapes

## 🚗 Project Overview

This project focuses on a **supervised classification problem** to distinguish between different types of vehicles based on their silhouette shapes. By leveraging various machine learning algorithms, we aim to build a robust model capable of accurately classifying vehicles into predefined categories. This is a classic example of a multi-class classification task where the goal is to predict a categorical label from a set of features.

<br>

## 📊 Dataset

The dataset used in this project is the **"Vehicle" dataset**, which contains features extracted from the silhouettes of different vehicles. The data consists of **846 instances** and **19 features**, with the target variable being the `class` of the vehicle. The classes are:

* **van** 🚐
* **car** 🚗
* **bus** 🚌

The features are numerical and describe various shape properties of the vehicle silhouettes, such as **compactness**, **circularity**, and **radius ratio**.

<br>

## ⚙️ Methodology

The project follows a structured machine learning workflow:

1.  **Data Preprocessing**: The initial step involves cleaning the data, which includes handling missing values through **mean imputation**.
2.  **Exploratory Data Analysis (EDA)**: **Univariate analysis** is performed to understand the distribution of each feature and identify any potential outliers or skewness.
3.  **Model Building**: A variety of supervised classification models are trained on the dataset, including:
    * **Logistic Regression**
    * **Decision Tree**
    * **Random Forest**
4.  **Model Evaluation**: The performance of each model is evaluated using various metrics such as **accuracy**, **precision**, **recall**, **F1-score**, and **ROC AUC score** to determine the best-performing model for this classification task.

<br>

## 🎯 Objective

The primary objective of this project is to compare the performance of different supervised learning algorithms on the vehicle shape classification problem and to identify the most effective model for this task. The insights gained from this analysis can be valuable for applications in automated vehicle recognition and classification systems.

---

## 🚀 Getting Started

### Prerequisites

* Python 3.x
* Jupyter Notebook or JupyterLab

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/DanMontHell/supervised-learning-classification-task-Masterschool.git](https://github.com/DanMontHell/supervised-learning-classification-task-Masterschool.git)
    cd supervised-learning-classification-task-Masterschool
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1.  **Launch Jupyter Lab:**
    ```sh
    jupyter lab
    ```

2.  **Open the notebook:**
    Open the `Daniel_Hellmuth_DA108_3_Supervised_ML_Vehicle_project.ipynb` file and run the cells to see the analysis and model results.

---
## 📂 Project Structure
```
.
├── Daniel_Hellmuth_DA108_3_Supervised_ML_Vehicle_project.ipynb
├── README.md
├── requirements.txt
└── data/
    └── vehicle.csv
```

---

## 🤝 Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to fork the repository and create a pull request.

---

## 📬 Contact
For insights, discussions, or collaboration opportunities, connect on [LinkedIn](https://www.linkedin.com/in/danhellmuth/).


## 📜 License
Distributed under the MIT License. See LICENSE for more information.

---

```txt
MIT License

Copyright (c) 2025 Daniel Hellmuth

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
