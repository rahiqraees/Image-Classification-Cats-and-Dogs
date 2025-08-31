# Image Classification: Cats vs. Dogs 🐱🐶

This project tackles a **binary image classification problem**: distinguishing between cats and dogs. Using **Convolutional Neural Networks (CNNs)** and transfer learning approaches, we evaluate different architectures and hyperparameter tuning methods to identify the most effective modeling strategy.

## 🔹 Project Overview
- Dataset: Cat vs. Dog images (binary classification)  
- Implemented **Simple CNN** and **Deep CNN** models from scratch  
- Applied **transfer learning** using **VGG16** (with and without tuning)  
- Explored **hyperparameter tuning** via Random Search and Bayesian Optimization  
- Analyzed results in terms of training/validation accuracy, loss curves, and generalization  

## 🔹 Key Findings
- **Deep CNN** consistently outperformed the Simple CNN across all key metrics (accuracy, loss, generalization)
- **VGG16 transfer learning** showed strong results, reducing training time and mitigating overfitting
- **Hyperparameter tuning**:
  - Random search → overfitting due to poor config selection and small tuning sample size  
  - Bayesian optimization → failed to converge with shallow search space exploration
- **Evaluation metrics**: Accuracy, binary cross-entropy, validation loss, and early stopping provided reliable model comparisons

## 🔹 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## 🔹 Repository Contents
- **`Project_code-1.ipynb`** → Full implementation of CNNs and experiments  
- **`condensed-1.pdf`** → Condensed project report with results and conclusions  

## 🔹 How to Run
```bash
# 1. Clone this repository
git clone https://github.com/rahiqraees/Cats-vs-Dogs-Classification.git

# 2. Open the notebook
jupyter notebook Project_code-1.ipynb

# 3. Run all cells to train and evaluate models
