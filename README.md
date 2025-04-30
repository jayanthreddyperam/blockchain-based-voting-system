# 🏡 House Price Prediction using Machine Learning

This project uses **XGBoost**, **Lasso Regression**, and **Neural Networks** to build predictive models for estimating house prices based on various features. The models are compared, and **Lasso Regression** achieved the highest accuracy at **92%**.

## 🔧 Technologies Used

- Python
- Pandas, Scikit-Learn
- XGBoost
- Lasso Regression
- Neural Networks (Keras)
- Matplotlib, Seaborn

## 📊 Results

- **Lasso Regression Accuracy**: 92%
- Compared with XGBoost and Neural Networks

## 📁 Project Structure

```
src/
├── train.py        # Training models
├── predict.py      # Making predictions
notebooks/
├── model_comparison.ipynb
data/
├── housing.csv     # Dataset used (if allowed)
```

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run training:
   ```bash
   python src/train.py
   ```

## 📈 Visualizations

Include accuracy plots, feature importance, etc.

![Model Comparison](visuals/accuracy_comparison.png)

## 📃 License

MIT License
