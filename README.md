# Binary Logistic Regression Implementation

##  Overview
This project features a Python implementation of a **Binary Logistic Regression** model, developed to explore the fundamental mechanics of supervised learning. It focuses on the process of transforming linear inputs into probabilities and optimizing model parameters through iterative learning. This was completed as a specialized assignment during my 2nd year of Computer Science.

##  Technical Implementation
In this project, I focused on implementing and studying the following core components:
* **Sigmoid Activation Function:** Used to map predictions to a probability range between 0 and 1.
* **Loss Function Logic:** Applied Binary Cross-Entropy (Log Loss) to evaluate the model's predictive accuracy.
* **Parameter Optimization:** Used Gradient Descent to update weights and biases, ensuring the model converges towards minimal error.
* **Vectorized Computations:** Leveraged **NumPy** for efficient matrix operations, ensuring performance and clean code structure.

##  Tech Stack
* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **Libraries:** NumPy (Data manipulation), Matplotlib (Visualization).

##  Results & Visualizations
The notebook demonstrates:
1. **Model Training:** The step-by-step logic of forward and backward passes.
2. **Loss Tracking:** A visualization showing the cost function decreasing over epochs, confirming the model is learning.
3. **MNIST Classification:** Evaluation of the model on a binary classification task using a subset of the MNIST dataset.

##  How to Run
1. Clone the repository or download the `.ipynb` file.
2. Install dependencies: `pip install numpy matplotlib`.
3. Open with Jupyter: `jupyter notebook Binary_Logistic_Regression.ipynb`.
