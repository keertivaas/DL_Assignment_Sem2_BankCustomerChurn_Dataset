## Bank Customer Churn Prediction: DNN from Scratch

A deep learning project built entirely from first principles to predict banking customer churn using a dataset of 10,000 clients. This project bypasses high-level frameworks like TensorFlow or PyTorch to implement core machine learning algorithms manually.

### Key Features

* **Baseline Logistic Regression:** Built from scratch using sigmoid activation, binary cross-entropy loss, and gradient descent with early stopping.


* **Multi-Layer Perceptron (MLP):** A deep neural network built from first principles featuring He initialization, ReLU hidden layers, a Sigmoid output layer, and a custom **Adam Optimizer**.


* **Hyperparameter Tuning:** Includes an automated grid search over network architectures and learning rates, backed by early stopping based on validation loss to prevent overfitting.


* **Performance Analysis:** Comprehensive evaluation comparing the models via loss curves, execution time, and classification metrics (Accuracy, Precision, Recall, and F1-Score).



### Results Summary

* **Baseline Logistic Regression:** Achieved **80.90% test accuracy** but struggled with class imbalance, yielding an **F1-score of 0.2765**.


* **Tuned MLP Network (`11 -> 128 -> 64 -> 32 -> 1`):** Drastically improved minority class recall, achieving **82.20% test accuracy** and a much stronger **F1-score of 0.5459**.
