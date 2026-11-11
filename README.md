# Python Assignment 2 – Data Visualization

## About the Project

This assignment is part of my Python Data Analytics learning journey. It focuses on exploring and visualizing taxi trip data using Python. The Seaborn Taxis dataset is used to practise data cleaning and create different charts to understand the data.

## Dataset Information

- **Dataset Name:** Taxis
- **Dataset Source:** Seaborn
- **Loading Function:** `sns.load_dataset("taxis")`

The dataset contains taxi trip details such as pickup time, distance, fare, tips, payment method, and pickup and dropoff locations.

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Work Completed

### 1. Data Loading and Exploration
- Loaded the Taxis dataset using Seaborn.
- Viewed the dataset using `head()`.
- Checked dataset information and column details.

### 2. Data Cleaning
- Checked missing values in the dataset.
- Identified missing values in categorical columns.
- Used mode to fill missing payment values.
- Removed rows with missing pickup and dropoff location details.
- Verified the dataset after cleaning.

### 3. Data Visualization

**Using Matplotlib and Pandas**
- Line Chart – Analysed fare changes over pickup time.
- Bar Chart – Compared total fare across pickup boroughs.
- Pie Chart – Displayed trip distribution by payment method.
- Histogram – Examined the distribution of trip distances.
- Box Plot – Compared tip amounts across pickup boroughs.

**Using Seaborn**
- Count Plot – Visualized the number of trips in each pickup borough.
- Scatter Plot – Explored the relationship between distance and fare.
- Heatmap – Displayed correlations between numerical columns.
- Pair Plot – Compared relationships between distance, fare, tip, and total across pickup zones.
- Violin Plot – Visualized fare distribution for different payment methods.

## Skills Practised

- Data cleaning and preprocessing
- Handling missing values
- Working with numerical and categorical data
- Creating charts using Matplotlib and Seaborn
- Understanding data distributions and relationships
- Basic Exploratory Data Analysis (EDA)

## How to Run the Project

1. Download or clone this repository.
2. Install the required Python libraries:

   `pip install pandas numpy matplotlib seaborn jupyter`

3. Launch Jupyter Notebook:

   `jupyter notebook`

4. Open the assignment notebook.
5. Run the code cells in sequence.

## Conclusion

Through this assignment, I gained practical experience in handling a real-world dataset and creating different visualizations using Python. It helped me improve my understanding of data cleaning, exploratory data analysis, and visual representation of data.
