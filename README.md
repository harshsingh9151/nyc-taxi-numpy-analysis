# 🚖 NYC Taxi Data Analysis with NumPy

A technical exploration of New York City taxi trip data using the **NumPy** library. This project focuses on high-performance data manipulation, vectorization, and boolean indexing to derive insights from a large-scale numerical dataset.

## 📌 Project Overview
The goal of this project was to move beyond high-level libraries like Pandas and perform raw data analysis using NumPy. By working with N-dimensional arrays, I calculated key performance indicators (KPIs) for taxi efficiency and passenger behavior.

### 📊 Key Insights
- **Average Speed:** Calculated the mean speed of all rides as **32 mph** (derived from distance and trip duration).
- **Airport Traffic:** Identified **11,832 drop-offs** at JFK Airport.
- **Tip Analysis:** Isolated high-value trips, finding only **16 rides** with tips exceeding $50.
- **Monthly Volume:** Filtered and counted **13,333 rides** specifically for the month of February.

## 🛠️ Tech Stack & Methods
- **Language:** Python 3.14
- **Library:** NumPy
- **Environment:** Jupyter Notebook

### Technical Skills Demonstrated:
* **Data Loading:** Using `np.genfromtxt()` to handle CSV parsing and header stripping.
* **Vectorization:** Performing arithmetic operations across entire columns without using slow Python loops.
* **Boolean Indexing:** Creating complex masks to filter data based on specific conditions (e.g., location codes, month identifiers).
* **Array Slicing:** Managing multidimensional data via index-based access.

## 📂 Dataset
The dataset 	`nyc_taxis.csv` contains information about pickup/dropoff locations, trip distances, durations, and fare breakdowns.


