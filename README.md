# ✈️ Airline Flights Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing airline flight data using Python for Data Analysis (DA). The main goal of the project is to clean, explore, and visualize airline flight data to discover useful insights such as airline frequency, departure trends, arrival trends, and overall flight patterns.

The project was completed using Jupyter Notebook and popular Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.

---

# 📂 Dataset Information

The dataset used in this project contains airline flight details such as:

* Airline Name
* Departure Time
* Arrival Time
* Flight Duration
* Ticket Price
* Source & Destination
* Flight Class
* Stops Information

Dataset File:
`airlines_flights_data.csv`

---

# 🛠️ Technologies Used

## Programming Language

* Python 🐍

## Libraries Used

* NumPy
* Pandas
* Matplotlib
* Seaborn

## Tools

* Jupyter Notebook
* VS Code / Jupyter

---

# 📊 Project Workflow

## 1️⃣ Importing Libraries

The required Python libraries were imported for data analysis and visualization.

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 2️⃣ Loading Dataset

The CSV dataset was loaded using Pandas.

```python
df = pd.read_csv('airlines_flights_data.csv')
```

---

## 3️⃣ Data Cleaning

Performed data cleaning operations such as:

* Removing unnecessary columns
* Checking missing values
* Changing data types
* Understanding dataset structure

Example:

```python
if 'index' in df.columns:
    df.drop(columns='index', inplace=True)
```

---

# 📈 Exploratory Data Analysis (EDA)

## ✅ Airline Frequency Analysis

Analyzed the number of flights operated by each airline.

### Operations Performed

* Unique airline count
* Airline names
* Frequency distribution
* Bar chart visualization

### Visualization

* Airline Frequency Bar Graph

---

## ✅ Departure Time Analysis

Analyzed departure time distribution of flights.

### Visualization

* Departure Time Distribution Graph

---

## ✅ Arrival Time Analysis

Studied arrival time frequency and patterns.

### Visualization

* Arrival Time Distribution Graph

---

## ✅ Duration Analysis

Converted duration column into integer type for analysis.

```python
df['duration'] = df['duration'].astype('int')
```

---

# 📌 Key Insights

* Some airlines operate significantly more flights than others.
* Flight departures are concentrated during specific time slots.
* Arrival patterns vary based on airline schedules.
* Data visualization helps identify flight trends easily.

---

# 📷 Sample Visualizations

## Airline Frequency Graph

* Shows airline-wise flight count.

## Departure Time Distribution

* Displays departure timing trends.

## Arrival Time Distribution

* Displays arrival timing patterns.

---

# 🚀 Future Improvements

* Add advanced visual dashboards
* Perform ticket price prediction
* Build machine learning models
* Add Power BI dashboard integration
* Create interactive charts using Plotly

---

# 📁 Project Structure

```bash
📦 Airline-Flights-Data-Analysis
 ┣ 📜 projec2.ipynb
 ┣ 📜 airlines_flights_data.csv
 ┣ 📜 README.md
```

---

# ▶️ How to Run the Project

1. Clone the repository

```bash
git clone <your-github-repo-link>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run `projec2.ipynb`

---

# 📚 Learning Outcomes

Through this project, I learned:

* Data Cleaning Techniques
* Exploratory Data Analysis (EDA)
* Data Visualization
* Working with Real-world Datasets
* Using Python Libraries for Analytics

---

# 👨‍💻 Author

Adnan Ali

📊 Aspiring Data Analyst
💡 Passionate about Data Analysis & Visualization

---

# ⭐ If You Like This Project

Give this repository a ⭐ on GitHub and support the project.
