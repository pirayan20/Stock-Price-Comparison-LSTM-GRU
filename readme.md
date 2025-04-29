# 📈 Stock Price Analysis (2005–2017)

This project analyzes historical stock market data from the [Kaggle dataset](https://www.kaggle.com/datasets/szrlee/stock-time-series-20050101-to-20171231), covering major tickers between 2005 and 2017.

It demonstrates:

- 📊 Exploratory Data Analysis using Pandas
- 📥 Dataset loading using `kagglehub`
- 📈 Time series trends for selected stock tickers

---

## 🚀 Getting Started

### 🔧 Dependencies

This project uses **Poetry** for package management.

Install dependencies with:

```bash
poetry install
```

If `kagglehub` is not already in your environment, add it:

```bash
poetry add kagglehub pandas matplotlib
```

---

### 📦 Dataset Download

This notebook uses `kagglehub` to download the dataset automatically:

```python
import kagglehub
path = kagglehub.dataset_download("szrlee/stock-time-series-20050101-to-20171231")
```

The dataset is downloaded to:

```
~/.cache/kagglehub/datasets/szrlee/stock-time-series-20050101-to-20171231
```

---

## 📓 How to Run the Notebook

1. Start your Poetry shell:

```bash
poetry shell
```

2. Launch Jupyter:

```bash
jupyter lab
# or
jupyter notebook
```

3. Open `stock_price.ipynb` and run all cells.

---

## 📁 File Structure

```
.
├── stock_price.ipynb       # Main notebook
├── README.md               # Project readme
├── pyproject.toml          # Poetry dependencies
```

---

## 📊 Data Source

- Dataset: [Stock Time Series 2005–2017](https://www.kaggle.com/datasets/szrlee/stock-time-series-20050101-to-20171231)
- Author: [Sean Szrlee](https://www.kaggle.com/szrlee)

---

## 📜 License

This project is for educational purposes. Refer to the original dataset license for any usage restrictions.
