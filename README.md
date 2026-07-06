CSV Data Explorer

A data analysis project built with Python, Pandas and Matplotlib.

The goal of this project is to explore datasets, perform exploratory data analysis (EDA) and extract business insights.

The first dataset analyzed is the Netflix Titles dataset.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## 🚧 In progress

## STEP BY STEP

✅ ## Sprint 1-Data Exploration
- Dataset loading with Pandas
- Dataset inspection
- Missing values analysis
- Descriptive statistics

✅ ## Sprint 2- Exploratory data analysy (EDA)
Business Question Answered: 
- Does Netflix offer more movies or TV shows?
- Which countries contribute the most content?
- How has Netflix content evolved over time?
- Which content ratings are the most common?

### Key Insights

- Movies dominate the Netflix catalog.
- The United States overwhelmingly dominates the dataset.
- Netflix content production peaked around 2018.
- Most Netflix titles are rated TV-MA, suggesting a focus on mature audiences.

✅ ## Sprint 3 - Data Cleaning

- Missing values handling
- Missing categorical values replaced with "Unknown"
- Rows with missing critical values removed
- Duplicate detection and removal
- Clean dataset exported for future analyses

✅ ## Sprint 4 - Adavanced Analysis With Groupby & Pivot Tables
- Learn how to group data using `groupby()`
- Perform statistical aggregations on grouped data
- Compare Movies and TV Shows using multiple metrics
- Create Pivot Tables for reporting and business analysis

Analyses Performed
- Average release year by content type
- Content count by type
- Rating distribution for Movies and TV Shows
- Top countries by number of titles
- Multiple statistical aggregations (`count`, `mean`, `min`, `max`)
- Creation of Pivot Tables for content analysis

### Key Insights
- TV Shows have a more recent average release year than Movies.
- Netflix's catalog is dominated by Movies.
- TV-MA is the most common rating for both Movies and TV Shows.
- The United States and India contribute the highest number of titles.
- Netflix's catalog is primarily oriented toward an adult audience.
- Movies exhibit a greater diversity of ratings than TV Shows.

### Skills Acquired

- Data aggregation with Pandas
- Multi-dimensional analysis
- Statistical summary interpretation
- Business insight extraction
- Data validation and extreme value analysis
- Pivot Table creation for reporting and dashboarding

✅** Sprint 5 - Combining Datasets

## Objectives

- Learn how to combine multiple DataFrames
- Understand the differences between `concat()`, `merge()` and `join()`
- Apply different types of joins
- Merge datasets using one or multiple keys
- Choose the appropriate merge strategy based on business requirements

## Key Commands Learned

| Command | Purpose | Description |
|----------|---------|-------------|
| `concat()` | Concatenation | Combines DataFrames vertically or horizontally |
| `merge()` | Dataset Integration | Combines DataFrames using one or more common keys |
| `join()` | Index-based Join | Joins DataFrames using the index |
| `set_index()` | Index Management | Sets a column as the DataFrame index |
| `how='inner'` | Inner Join | Keeps only matching records |
| `how='left'` | Left Join | Keeps all rows from the left DataFrame |
| `how='right'` | Right Join | Keeps all rows from the right DataFrame |
| `how='outer'` | Outer Join | Keeps all rows from both DataFrames |

## Analyses Performed

- Vertical and horizontal concatenation with `concat()`
- Dataset integration using `merge()`
- Index-based joins with `join()`
- Merge operations using multiple keys
- Comparison of different join strategies

## Key Insights

- `concat()` combines DataFrames without requiring a common key.
- `merge()` combines DataFrames using one or more common columns.
- `join()` is a simplified alternative when working with indexes.
- Multiple merge keys improve data integrity when a single key is not sufficient.
- The choice of join (`inner`, `left`, `right`, `outer`) depends on the business question rather than the syntax.

## Skills Acquired

- Dataset integration with Pandas
- Understanding relational joins
- Working with indexes
- Managing multiple merge keys
- Selecting the appropriate join strategy for business scenarios
