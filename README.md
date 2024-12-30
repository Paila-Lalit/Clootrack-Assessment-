# Clootrack-Assessment-
# Clootrack Data Analysis Assessment

This repository contains the data analysis project conducted by **Lalit Kumar Paila**. The objective was to extract meaningful insights from customer reviews using Python-based data analysis techniques.

## Dataset Overview

- **Dataset Name**: `Data Analyst - Test Data - US.csv`
- **Size**: 6,448 rows and 3 columns (`Review`, `date`, `Location`)
- **Key Features**:
  - Customer reviews of services.
  - Date of the review.
  - Review location.

## Objectives

1. Clean and preprocess the dataset to ensure data quality.
2. Perform exploratory data analysis (EDA) to identify trends and patterns.
3. Visualize insights to support decision-making.

---

## Project Workflow

### 1. **Data Cleaning**
   - Handled missing values:
     - **`Location` column**: 4,737 missing values identified.
   - Standardized date formats (e.g., corrected entries like `Dec 2018` and `Aug 2018`).
   - Removed duplicate entries to ensure data reliability.

### 2. **Exploratory Data Analysis**
   - Computed unique values for each column to understand the data structure.
   - Checked for anomalies and symbols in the `Review` column.
   - Visualized missing data using a heatmap.
   - Created a histogram to show the distribution of reviews over time.

### 3. **Key Insights**
   - **High Engagement Locations**:
     - Majority of reviews originated from the United States.
   - **Customer Concerns**:
     - Common complaints included poor internet connectivity and uncomfortable beds.
   - **Positive Highlights**:
     - Customers frequently praised the friendliness of staff and location convenience.
   - **Seasonal Trends**:
     - Peak activity observed during specific months, indicating opportunities for targeted marketing campaigns.

### 4. **Visualization Tools**
   - Used Python libraries such as `Matplotlib`, `Seaborn`, and `Pandas` for analysis and visualization.

---

## Results

- **Data Quality**: Enhanced dataset by resolving missing and inconsistent values.
- **Insights for Improvement**:
  - Address key customer concerns like internet quality and room comfort.
  - Leverage positive feedback for marketing campaigns.
- **Actionable Opportunities**:
  - Focus on high-engagement regions like the United States.
  - Plan promotional strategies for peak review months.

---

## Technologies Used

- **Python Libraries**:
  - `Pandas`
  - `NumPy`
  - `Matplotlib`
  - `Seaborn`

---

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone <repository-url>
