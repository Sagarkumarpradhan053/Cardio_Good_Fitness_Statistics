# Cardio Good Fitness Case Study - Descriptive Statistics

## Project Description
This notebook performs a descriptive analysis on the Cardio Good Fitness dataset to understand customer profiles for different treadmill products (TM195, TM498, TM798). The goal is to help the market research team identify distinct customer characteristics associated with each product line.

## Data Source
The data is stored in the `CardioGoodFitness.csv` file. It contains information about individuals who purchased a treadmill during the prior three months. Key variables include:

*   **Product:** Treadmill model (TM195, TM498, TM798)
*   **Gender:** Male or Female
*   **Age:** In years
*   **Education:** In years
*   **MaritalStatus:** Single or Partnered
*   **Income:** Annual household income
*   **Usage:** Average number of times the customer plans to use the treadmill each week
*   **Fitness:** Self-rated fitness on a 1-to-5 scale
*   **Miles:** Average number of miles the customer expects to walk/run each week

## Analysis Performed
The notebook includes the following analytical steps:

1.  **Data Loading and Inspection:** Loading the dataset and examining its structure, descriptive statistics, and data types.
2.  **Univariate Analysis:** Visualizing the distribution of individual variables using histograms and box plots.
3.  **Bivariate Analysis:** Exploring relationships between variables, such as:
    *   Cross-tabulations between categorical variables (e.g., Product vs. Gender, Product vs. MaritalStatus).
    *   Correlation matrix for numerical variables.
    *   Pivot tables to aggregate data by different categories (e.g., Income by Product, Gender, and MaritalStatus).
4.  **Data Visualization:** Using libraries like `matplotlib` and `seaborn` to create various plots, including histograms, box plots, and heatmaps to understand data distributions and correlations.

## How to Run the Notebook

1.  **Open in Google Colab:** Upload the notebook to your Google Drive and open it with Google Colab.
2.  **Load Data:** Ensure the `CardioGoodFitness.csv` file is accessible (e.g., by providing the correct Google Drive file ID if it's stored there). The notebook contains a cell to load the data using a `file_id`.
3.  **Run Cells:** Execute each cell sequentially. The output of each analysis step will be displayed below the respective code cell.
