# 👟 Shoes Sales Data – EDA

Exploratory Data Analysis of a shoe sales dataset using Python, Pandas & Seaborn: data cleaning, outlier detection, brand/shoe-type/country analysis, correlation heatmap and business insights on sales & revenue.

## 🗂️ Dataset

| Column        | Description               |
|---------------|---------------------------|
| `Date`        | Date of sale              |
| `Brand`       | Shoe brand                |
| `Country`     | Country of sale           |
| `Shoe_Type`   | Category of shoe          |
| `Price_USD`   | Price per pair (USD)      |
| `Units_Sold`  | Units sold                |
| `Revenue_USD` | Total revenue (USD)       |

## 🔍 What I Did

- Loaded and inspected data, converted `Date` to datetime
- Checked missing values and duplicates
- Univariate analysis (histograms, count plots)
- Outlier detection using IQR method and boxplots
- Bivariate analysis and brand / shoe-type comparisons
- Correlation analysis

## 📊 Visualizations

### Price vs Revenue
![Price vs Revenue](images/graph.png)

### Correlation Matrix
![Correlation Matrix](images/correlation.png)

## 💡 Key Insights

- **New Balance** generated the highest total revenue, while **Nike** generated the lowest.
- **Skechers** sold the most units overall; **Nike** sold the fewest.
- **Sneakers** are the best-selling shoe type; **Sports** shoes sell the least.
- **Skechers** had the highest sales among brands in **France**.

## 🛠️ Tech Stack

Python • NumPy • Pandas • Matplotlib • Seaborn • Jupyter Notebook

## 🚀 How to Run

1. Clone the repo and place `shoes_sales_dataset.csv` in the project folder
2. Install dependencies: `pip install numpy pandas matplotlib seaborn jupyter`
3. Open `EDA_shoes_data_analysis.ipynb` and run all cells
