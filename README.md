# 🛒 Blinkit Sales Analysis

An exploratory data analysis (EDA) project on Blinkit grocery sales data, built with Python. The notebook cleans the raw dataset, calculates key business KPIs, and visualizes sales performance across product categories, outlet types, locations, and more.

---

## 📌 Project Overview

Quick-commerce platforms like Blinkit sell thousands of products across many outlets. This project answers questions such as:

- How much total revenue is generated, and what is the average sale value?
- Which item types and fat-content categories drive the most sales?
- How do outlet size, location tier, and establishment year affect sales?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas | Data loading, cleaning, aggregation |
| NumPy | Numerical operations |
| Matplotlib | Charts and plots |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive analysis |

---

## 📂 Repository Structure

```
Blinkit-Analysis/
│
├── rawdata/
│   └── blinkit_data.csv        # Raw dataset
├── Blinkit_Analysis.ipynb      # Main analysis notebook
└── README.md
```

---

## 🧹 Data Cleaning

The `Item Fat Content` column contained inconsistent labels. These were standardized:

| Original | Cleaned |
|----------|---------|
| `LF`, `low fat` | `Low Fat` |
| `reg` | `Regular` |

---

## 📊 KPIs Calculated

- **Total Sales**: sum of all sales
- **Average Sales**: mean sales per item
- **Number of Items Sold**: count of item records
- **Average Rating**: mean customer rating

---

## 📈 Visualizations

1. **Sales by Fat Content**: pie chart
2. **Sales by Item Type**: bar chart, sorted by revenue
3. **Sales by Outlet Location Type and Fat Content**: grouped bar chart
4. **Sales by Outlet Establishment Year**: line chart
5. **Sales by Outlet Size**: pie chart
6. **Sales by Outlet Location Type**: horizontal bar chart

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Blinkit-Analysis.git
   cd Blinkit-Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Update the data path** in the notebook to match your local setup:
   ```python
   df = pd.read_csv("rawdata/blinkit_data.csv")
   ```

4. **Launch the notebook**
   ```bash
   jupyter notebook Blinkit_Analysis.ipynb
   ```

---

## 🔍 Key Insights


> - Low Fat items contribute 64.6% of total sales.
> - The top-selling item type is Fruits and Vegetables.
> - Tier 3 outlets generate the highest revenue.
> - Medium size outlets account for the largest share of sales.

---

## 🔮 Future Improvements


- Add correlation analysis between item visibility, MRP, and sales
- Build a sales prediction model
- Add outlet-wise and item-wise performance rankings

---

## 👤 Author

**Hisham**

- GitHub: [Hisham1925](https://github.com/Hisham1925)
- LinkedIn: [Hisham S](https://www.linkedin.com/in/3hisham-s/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).