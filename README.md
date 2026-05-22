# Data Cleaning and Exploration using Pandas

## Overview
This project demonstrates basic data engineering and data preprocessing tasks using Python and Pandas on an e-commerce dataset.

The assignment focuses on:
- Loading and exploring CSV data
- Handling missing values
- Removing duplicate records
- Performing basic data operations
- Creating derived columns
- Exporting cleaned data

---

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

---

## Dataset
The dataset used is:

```text
Combined_dataset.csv
```

It contains product-related information such as:
- Product details
- Ratings
- Prices
- Seller information
- Variations
- Customer reviews

---

## Tasks Performed

### 1. Data Loading
- Loaded CSV dataset into a Pandas DataFrame.

### 2. Data Exploration
Performed:
- `head()`
- `tail()`
- `shape`
- `columns`
- `info()`

to understand dataset structure.

### 3. Handling Missing Values
- Filled missing text values using `"Not Available"`
- Filled missing numerical values using mean values

### 4. Data Cleaning
- Removed duplicate rows
- Handled missing values appropriately

### 5. Data Operations
- Filtered rows
- Selected specific columns

### 6. Feature Engineering
Created:
- `quantity`
- `total_amount`

where:

```python
total_amount = initial_price * quantity
```

### 7. Exporting Cleaned Data
Saved cleaned dataset as:

```text
cleaned_dataset.csv
```

---

## Project Structure

```text
├── Combined_dataset.csv
├── cleaned_dataset.csv
├── data_cleaning_assignment.ipynb
├── README.md
```

---

## How to Run

### Install Dependencies

```bash
pip install pandas numpy jupyter
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
data_cleaning_assignment.ipynb
```

---

## Output
- Cleaned dataset CSV file
- Jupyter Notebook containing all preprocessing steps
- Summary of data cleaning operations

---

## Author
Priyansh Ahlawat