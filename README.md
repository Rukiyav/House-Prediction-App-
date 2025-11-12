# House-Prediction-App



## 🏠 House Price Prediction App

This is a simple Streamlit web application that uses **Linear Regression** to predict house prices based on their size. It generates synthetic data, trains a model, and provides interactive predictions with visualizations.

---

### 🚀 Features

- Generates synthetic house size and price data using NumPy
- Trains a Linear Regression model using scikit-learn
- Interactive input for house size
- Predicts house price and displays it with formatting
- Visualizes the prediction on a scatter plot using Plotly

---

### 📦 Dependencies

Make sure you have the following Python packages installed:

```bash
streamlit
numpy
pandas
plotly
scikit-learn
```

Install them using:

```bash
pip install streamlit numpy pandas plotly scikit-learn
```

---

### 📁 File Structure

```
House-Prediction-App-/
│
├── main.py           # Streamlit app script
├── README.md         # Project documentation
```

---

### ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone git@github.com:Rukiyav/House-Prediction-App-.git
   cd House-Prediction-App-
   ```

2. Run the Streamlit app:
   ```bash
   streamlit run main.py
   ```

3. Open the app in your browser and enter a house size to get a price prediction.

---

### 📊 Visualization

The app displays a scatter plot of synthetic house data and highlights your prediction in **red** for easy comparison.

---

### 🧠 Model Details

- **Data Generation**: House sizes are sampled from a normal distribution centered at 1400 sqft.
- **Price Calculation**: Prices are linearly dependent on size with added noise.
- **Model**: Simple Linear Regression trained on 80% of the generated data.

---

### 👩‍💻 Author

**Vaishnavi**  
Email: `nvaishnavi005@gmail.com`


