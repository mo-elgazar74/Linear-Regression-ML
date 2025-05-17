# E-Commerce Customer Behavior: Linear Regression from Scratch

This project demonstrates a **linear regression implementation from scratch** (no high-level ML libraries) to predict **Yearly Amount Spent** by customers based on behavioral metrics in an e-commerce platform.

## 📊 Dataset

We use the [E-Commerce Customer Behavior dataset](https://www.kaggle.com/datasets/mohamedelgazar74/dataset) from Kaggle, which contains user information such as:

- Average Session Length  
- Time on App  
- Time on Website  
- Length of Membership  
- Yearly Amount Spent (Target)

Download the dataset and place the CSV file (e.g., `Ecommerce Customers.csv`) in the same directory as the notebook.

## 📁 Files

- `linear-rgression-from-scratch.ipynb` — Main notebook implementing:
  - Data loading and preprocessing
  - Feature engineering and scaling
  - Linear Regression from scratch using:
    - Batch Gradient Descent (GD)
    - Ridge Regression (L2 regularization)
    - Stochastic Gradient Descent (SGD)
  - Evaluation metrics and visualizations

- `README.md` — This overview and setup guide

## 🧠 ML Techniques Used

- Linear Regression without using `scikit-learn`
- Mean Squared Error (MSE) for loss calculation
- Gradient Descent variants
- Regularization with Ridge Regression
- Seaborn/Matplotlib visualizations

## 📈 Visualization Example

The notebook includes a custom function to visualize how well the model predicts spending:

```python
plot_predictions(y_test, y_pred, "Linear Regression", style='whitegrid', palette=('purple', 'gray'))
```

Features:
- Supports multiple Seaborn styles
- Clean comparison between actual vs. predicted values
- Customizable colors

## ▶️ Getting Started

1. Clone this repo or download the files manually.
2. Install the required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mohamedelgazar74/dataset) and place it in your project directory.
4. Run the notebook `linear-rgression-from-scratch.ipynb`.

## 📌 Future Improvements

- Add feature importance visualization
- Try Lasso and ElasticNet regression
- Include categorical feature encoding (e.g., `Avatar` color)
- Add train-validation split for better generalization

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### ✨ Contributions Welcome!
