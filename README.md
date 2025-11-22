📊 Data Analysis on CSV Files (Sales Data)
📌 Objective

Analyze a sales dataset to extract insights using Python & Pandas.

🛠 Tools Used

Python

Pandas

VS Code / Jupyter Notebook / Google Colab

📂 Deliverables

.ipynb Notebook

At least one chart (bar/line/pie)

🔎 Steps (Mini-Guide)

Cell 1: Import libraries

import pandas as pd
import matplotlib.pyplot as plt


Cell 2: Load CSV file

df = pd.read_csv("sales.csv")
df.head()


Cell 3: Analyze

df.groupby("Product")["Sales"].sum()


Cell 4: Plot

df.groupby("Product")["Sales"].sum().plot(kind="bar")
plt.xlabel("Product")
plt.ylabel("Total Sales")
plt.title("Sales Analysis")
plt.show()

✅ Outcome

You will learn:

How to load and analyze CSV files

Use of groupby(), sum()

How to generate basic charts in Python
