# Cryptocurrency Data Analysis (BTC-USD)

This project performs a comprehensive data analysis of Bitcoin (BTC) prices from 2021 to 2022. It demonstrates key data science skills including data loading, statistical analysis, visualization, and hypothesis testing. The project uses a real-world dataset to explore price trends and relationships between different price points.

<br>

---

### Features

* **Data Loading and Inspection**: The notebook loads a dataset of historical BTC prices, showing the total number of records and a preview of the data.
* **Descriptive Statistics**: Calculates key statistical measures for the 'Close' prices, such as mean, median, mode, variance, and standard deviation, to understand the data's central tendency and dispersion.
* **Data Visualization**: Creates a histogram to show the distribution of 'Close' prices and a scatter plot to analyze the relationship between 'Open' and 'Close' prices.
* **Linear Regression**: Applies a linear regression model to predict the 'Close' price based on the 'Open' price, with the results visualized in a regression line plot.
* **Statistical Testing**: Conducts an independent t-test to determine if there is a significant difference in the average 'Close' prices of BTC between 2021 and 2022.

<br>

---

### Technologies Used

* **Python**: The core programming language for the project.
* **Pandas**: Used for data manipulation and statistical analysis.
* **Matplotlib**: Utilized for creating various data visualizations, including histograms and scatter plots.
* **SciPy**: Used to perform the statistical t-test.
* **Jupyter Notebook**: The environment where the analysis and code are executed.

<br>

---

### Getting Started

To run this project, you will need to clone the repository, install the necessary dependencies, and have the dataset available.

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/Manarsenic/your_repo_name.git](https://github.com/Manarsenic/your_repo_name.git)
    cd your_repo_name
    ```

2.  **Install dependencies**:
    * It is recommended to use a virtual environment.
    * Install all required libraries.
    ```bash
    pip install pandas matplotlib scipy
    ```

3.  **Download the dataset**:
    * The notebook uses a CSV file named `BTC-USD.csv`.
    * Download the dataset and place it in the project directory.

4.  **Run the notebook**:
    * Open `CRYPTO(5).ipynb` in your Jupyter Notebook or Google Colab environment.
    * Execute the cells in order to see the full analysis and results.
