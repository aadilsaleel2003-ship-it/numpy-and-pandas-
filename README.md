🚗 NumPy & Pandas Analysis – Auto MPG Dataset

📌 Overview

This project demonstrates basic to intermediate data analysis using NumPy and Pandas on the Auto MPG dataset.
It covers array operations, filtering, handling missing data, grouping, and exporting results.

---

📂 Dataset

- Dataset used: Auto MPG Dataset
- Features include:
  - "mpg"
  - "cylinders"
  - "displacement"
  - "horsepower"
  - "weight"
  - "acceleration"
  - "model year"
  - "origin"
  - "car name"

---

⚙️ Technologies Used

- Python 🐍
- NumPy
- Pandas

---

🔢 NumPy Tasks

1. Basic Array Operations

- Converted "mpg" column into NumPy array
- Calculated:
  - Mean
  - Median
  - Standard Deviation
- Counted cars with "mpg > 25"

2. Filtering

- Filtered cars with more than 6 cylinders
- Extracted car names as a list

3. Broadcasting

- Increased "horsepower" by 10%
- Handled missing values using mean

4. Boolean Indexing

- Found average "displacement" for European cars ("origin = 2")

5. Conditional Aggregation

- Calculated mean "mpg" grouped by "cylinders"

---

📊 Pandas Tasks

1. Basic Exploration

- Displayed first 10 rows
- Checked dataset shape
- Generated summary statistics

2. Filtering & Indexing

- Selected cars from year 1975 with "weight < 3000"
- Displayed:
  - Car Name
  - Weight
  - MPG

3. Handling Missing Data

- Checked for null values
- Replaced missing "horsepower" values with median

4. Data Transformation

- Created new column:
  - "power_to_weight_ratio = horsepower / weight"

5. Group By

- Grouped by "origin"
- Calculated average "mpg"

6. Visualization Preparation

- Created summary grouped by "model year"
- Calculated average:
  - mpg
  - weight
  - horsepower

7. Exporting Data

- Filtered cars with "mpg > 30"
- Exported to CSV:
  - "high_mpg_cars.csv"

---

 Real-world dataset handling

---
