
# Women's E-Commerce Clothing Reviews: Linear Regression from Scratch

This project demonstrates a linear regression implementation **from scratch** (no high-level ML libraries) to predict user ratings based on review data from a real-world dataset.

## 📊 Dataset

We use the [Women's E-Commerce Clothing Reviews dataset](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews) from Kaggle, which contains thousands of customer reviews including text, ratings, and various product attributes.

Download the dataset and place the CSV file (`Womens Clothing E-Commerce Reviews.csv`) in the same directory as the notebook.

## 📁 Files

- `linear-rgression-from-scratch.ipynb` — Main notebook implementing:
  - Data preprocessing
  - Feature engineering
  - Linear regression using:
    - Batch Gradient Descent (GD)
    - Ridge Regression (L2)
    - Stochastic Gradient Descent (SGD)
  - Evaluation and visualization

- `README.md` — Project overview and instructions.

## 🧠 ML Techniques Used

- Linear Regression from scratch (no `scikit-learn`)
- Mean Squared Error (MSE) loss
- Gradient descent optimizers
- Regularization (Ridge)
- Visualizations comparing predictions vs true ratings

## 📈 Visualization Example

We include a custom visualization function to compare model predictions with true values:

```python
plot_predictions(y_test, y_pred, "Model Name", style='whitegrid', palette=('blue', 'red'))
```

Supports:
- Seaborn styles: `whitegrid`, `dark`, `ticks`, etc.
- Custom color palettes
- Adjustable font and layout

## ▶️ Getting Started

1. Clone this repo or download the files.
2. Install requirements:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Download the dataset from Kaggle [here](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews) and place the CSV file in your project folder.
4. Run the notebook `linear-rgression-from-scratch.ipynb`.

## 📌 Future Improvements

- Add text-based feature engineering (e.g., sentiment analysis)
- Try polynomial regression
- Add model saving/loading
- Cross-validation support

## 📜 License

This project is for educational purposes. No warranty is provided. Dataset copyright belongs to the original creators.

---

### ✨ Contributions welcome!
