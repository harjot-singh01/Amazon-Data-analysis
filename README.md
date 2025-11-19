⭐ README — Amazon Sales Data Analysis Project
📌 Project Overview

This project focuses on cleaning, analyzing, and visualizing Amazon sales data using Python.
It includes data preprocessing, state-wise correction of ship-state values, category-wise insights, order status distribution, and several graphical visualizations to understand sales patterns.

The analysis helps answer key business questions such as:

Which states generate the highest revenue?

Which categories/products sell the most?

What percentage of orders get cancelled or returned?

How many items are shipped vs delivered?

Which product categories drive maximum revenue?

📂 Dataset

The dataset used in this project is named:

Amazon Sale Report.csv

Columns include:

order_id

category

size

status

ship-state

amount (sales amount)

date

and other Amazon order details.

🧹 Data Cleaning

Data cleaning performed includes:

✔ Removing duplicates
✔ Handling missing values
✔ Cleaning amount column

Converted from string format like "₹1,299" → 1299.0.

✔ Cleaning ship-state column

Removed special characters

Fixed misspelled state names

Standardized all states (e.g., "Karntaka" → "Karnataka")

✔ Normalizing categorical columns

Such as status, category, and size.

📊 Data Analysis Performed
🔹 Category Analysis

Category-wise total sales

Category-wise product count

Category vs size distribution

🔹 State Analysis

State-wise total sales

State-wise order count

Top revenue-generating states

🔹 Order Status Analysis

Delivered vs Shipped vs Cancelled

Pie chart distribution with grouped “Others” statuses

Identifying which products get cancelled frequently

📈 Visualizations Included

All graphs created using matplotlib:

📌 1. State-wise Total Sales Bar Graph

Shows the contribution of each Indian state to total revenue.

📌 2. Category-wise Sales Bar Graph

Helps understand top-performing categories.

📌 3. Order Status Pie Chart (Cleaned)

Grouped minor statuses into Others for readability.

📌 4. Category-wise Product Count

Visualizes how many products belong to each category.

📌 5. Heatmaps (If enabled)

For correlation between numeric features.

🧠 Key Insights

Maharashtra and Karnataka are the top revenue-generating states.

Shipped and delivered orders dominate total orders (~80%+).

Cancelled orders form a significant minority (~10–15%).

Few categories drive most of the revenue.

🛠 Technologies Used

Python 3.9+

Pandas

NumPy

Matplotlib

Seaborn (optional)

Jupyter Notebook

🤝 Contributing

Feel free to submit pull requests or open issues to suggest improvements.

📧 Contact

For any queries or support:
Harjot Singh
