# 🧾 Retail Sales Analysis using SQLite and Python

## 👋 Introduction
This project is a simple yet realistic simulation of how a data analyst might analyze retail sales data using **SQLite**, **Python**, and **Matplotlib**. I wanted to go beyond just running SQL queries — so I created a mini end-to-end setup that includes a mock dataset, SQL queries, visual insights, and a professional workflow.
It is a small project, but it reflects how I think as a data analyst: structure the data properly, ask meaningful questions, and communicate results clearly.

## 📂 Project Overview
1. Built a normalized sales table with extra dimensions like `region`, `category`, and `payment_method`
2. Inserted 40+ randomized transactions to simulate real business variation
3. Queried product-level and category-level performance using SQL
4. Visualized total revenue by product using `matplotlib`
5. Highlighted top-performing products with summary insights

## 📊 Dataset Details
The SQLite database (`sales_data.db`) contains one table: `sales`
| Column           | Description                          |
|------------------|--------------------------------------|
| `id`             | Unique transaction ID                |
| `date`           | Date of sale (YYYY-MM-DD)            |
| `product`        | Product name                         |
| `category`       | Product category (e.g., Stationery)  |
| `quantity`       | Quantity sold                        |
| `price`          | Price per unit (₹)                   |
| `region`         | Sales region (North, South, etc.)    |
| `payment_method` | Cash, Card, UPI, or Net Banking      |

## 🔍 Insights & Observations
1. The product generating the highest revenue was **Notebook** from the **Stationery** category — contributing over ₹1200 in total.
2.Sales are well distributed across regions and payment methods, indicating healthy channel diversity.
3.Highlighters, Pens, and Staplers also performed strongly in revenue contribution.

(You can verify this by checking the plot and the SQL output in the notebook.)

## 🧪 Tools Used
1. **SQLite** (via Python’s built-in `sqlite3`)
2.**Pandas** for reading SQL query outputs
3.**Matplotlib** for visualization
4.**Google Colab** for notebook execution

▶️ How to Use
1. Clone this repository or download the files
2. Open the notebook: `sales_analysis.ipynb` in Google Colab or Jupyter
3. Run all cells to:
   i. Create the database
   ii.Insert sample data
   iii.Run SQL queries
   iv. Generate the revenue plot

## 🙋‍♂️ About Me
Hi, I am Ankit — an aspiring data analyst who enjoys blending logic, storytelling, and technical tools to uncover insights from data.  
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/ankit-narayan-singh-74852a216?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

Thanks for reading! 😊 If you found this helpful or interesting, feel free to ⭐ the repo.

   
