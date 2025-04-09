
---

## 📊 Visualizations

### 1. Total Global Sales by Year
Shows the trends in overall game sales over time.

![Total Sales](docs/images/graph_page3_1.png)

### 2. Genre Distribution by Platform
Highlights how different game genres are distributed across gaming platforms.

![Genre by Platform](docs/images/graph_page3_2.jpeg)

---

## 🔍 Forecasting Results

### 3. ARIMA Forecast
ARIMA captures trends and seasonality to make predictions.

![ARIMA Forecast](docs/images/graph_page4_1.png)

### 4. ETS Forecast
ETS (Error, Trend, Seasonality) model output.

![ETS Forecast](docs/images/graph_page4_2.png)

### 5. TBATS Forecast
TBATS handles multiple seasonality and complex patterns.

![TBATS Forecast](docs/images/graph_page4_3.png)

---

## ⚙️ Models Used

| Model  | Strengths                                | Notes                       |
|--------|-------------------------------------------|-----------------------------|
| ARIMA  | Captures autoregressive trends + noise   | Requires stationarity       |
| ETS    | Great for exponential smoothing          | Easy to interpret           |
| TBATS  | Handles multiple seasonal patterns        | Ideal for complex signals   |

---

## 🧪 Evaluation Metrics

Each model was evaluated using:

- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **MAPE (Mean Absolute Percentage Error)**

> See full results and comparison in [`evaluation.R`](scripts/evaluation.R)

---

## 📂 Data

- Source: [Kaggle Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogame-sales-with-ratings)
- File: [`sample_data.csv`](sample_data.csv)

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/rushab0407/video-game-sales-forecasting.git
