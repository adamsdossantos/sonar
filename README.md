# Logistic Regression Machine Learning Project - Sonar Data

## 1. Project Overview

This project implements a Logistic Regression model for a sonar to identify if it is a rock or a mine. Logistic Regression is a statistical model used for binary classification tasks, estimating the probability that an instance belongs to a particular class.



## 2. Features
- Data Preprocessing: Data cleaning, normalization, and splitting into training and testing sets.
- Model Training: Training an SVM model using scikit-learn.
- Model Evaluation: Evaluating the performance of the model using metrics such as accuracy, precision, recall, and F1-score.
- Visualization: Visualization of the decision boundary and the ROC curve.


## 3. Project Structure
    ├── sonar_data.csv              # Dataset file 
    ├── sonar.ipynb                 # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 4. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/sonar.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook sonar.ipynb
```
## 5. Usage

Open the sonar.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- Data Loading and Preprocessing: Load data from data/ folder and perform necessary preprocessing.
- Model Training: Train an SVM model with adjustable hyperparameters.
- Model Evaluation: Evaluate the model using accuracy, precision, recall, F1-score, and AUC-ROC curve.

## 6. Results in Test
| Metric    |  Value   |
|-----------|----------|
| Accuracy  |  XX%   |
| Precision |  XX%   |
| Recall    |  XX%   |
| F1-Score  |  XX%   |
| AUR-ROC Curve| XX% |

## 7. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 8. License

This project is licensed under the MIT License - see the LICENSE file for details.







