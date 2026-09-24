# Data-Analytics-project

README.md

100%
# Data Analysis of a Super Store Dataset

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a Super Store dataset to identify sales and profitability patterns and areas where profitability can be improved.

The analysis uses Python with Pandas, NumPy, Matplotlib, and Seaborn. It examines profitability by category, sub-category, segment, region, country, state, and city.

## Objectives

- Understand the overall sales and profit performance of the Super Store.
- Calculate profit percentage over sales.
- Compare the three major product categories.
- Identify sub-categories contributing to profit or loss.
- Analyze sales and profit across regions, states, and cities.
- Compare customer segments.
- Identify products/categories that may require attention to reduce losses.
- Answer practical business questions using the dataset.

## Dataset

The notebook expects a CSV file named:

`superstore_dataset.csv`

The CSV file must be placed in the **same folder as the Jupyter Notebook** before running the project.

The notebook uses fields including:

- Region
- Country
- State
- City
- Ship Mode
- Category
- Sub-Category
- Segment
- Sales
- Profit
- Quantity

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Data Loading and Inspection

The dataset is loaded using Pandas. The notebook checks:

- Dataset contents
- Columns
- Unique regions
- Shipping modes
- Number of cities
- Data types and information
- Descriptive statistics
- Missing values

The notebook reports that there are no null values in the dataset.

### 2. Profit Percentage

A new column called `Profit %` is calculated as:

`Profit % = Profit / Sales × 100`

This is used to compare profitability relative to sales.

### 3. Category Analysis

Sales and profit are grouped by:

- Furniture
- Office Supplies
- Technology

A pie chart is used to visualize each category's contribution to total profit.

### 4. Sub-Category Analysis

The project investigates sub-categories within each major category.

The notebook identifies **Bookcases and Tables** in Furniture as areas requiring attention because of their profitability.

For Office Supplies, the notebook highlights **Paper and Binders** as major profit contributors and notes losses associated with **Supplies**.

For Technology, the notebook observes that the category contributes strongly to profit and that no item is identified as being sold at a loss in the analysis.

### 5. Geographic Analysis

Sales and profit are analyzed by:

- Region
- Country
- State
- City

Top cities by sales and profit are also visualized.

### 6. Segment Analysis

The project compares:

- Consumer
- Corporate
- Home Office

The notebook identifies Consumer as the largest contributor to profit among these segments.

### 7. Visualization

The project uses:

- Pie charts
- Bar charts
- Scatter plots
- Line plots

These visualizations are used to communicate sales and profitability patterns.

## Key Findings Reported by the Notebook

According to the analysis contained in the submitted notebook:

1. The Super Store is reported to make approximately **12.4% profit over total sales**.
2. **Office Supplies** has the highest quantity sold among the categories.
3. **Furniture** requires attention, particularly **Bookcases and Tables**, because of profitability concerns.
4. **Paper and Binders** are identified as important profit contributors within Office Supplies.
5. **Supplies** are identified as a loss-making sub-category in the notebook's analysis.
6. **Technology** is described as a major profit contributor, with no loss-making item identified in the analysis.
7. The **Consumer** segment is reported as the largest contributor to profit.
8. The notebook estimates that approximately **one and a half lakh** of loss could potentially be avoided if certain loss-making items were discontinued. This is an analytical estimate from the notebook and should be validated against the underlying dataset before business use.

## How to Run

### Step 1: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 2: Place the dataset

Put:

```text
superstore_dataset.csv
```

in the same directory as the notebook.

### Step 3: Open the notebook

```bash
jupyter notebook
```

Open the project `.ipynb` file.

### Step 4: Run all cells

Run the notebook from top to bottom.

## Project Structure

```text
Superstore_Project/
│
├── project_notebook.ipynb
├── superstore_dataset.csv
├── requirements.txt
├── README.md
└── Project_Report.docx
```

## Important Note

The notebook depends on the external file `superstore_dataset.csv`. The CSV is not embedded in the notebook. Therefore, anyone reproducing the project must provide the dataset with the expected filename and required columns.

## Author

**Dharani**

## Project Title

**Data Analysis of a Super Store Dataset**
