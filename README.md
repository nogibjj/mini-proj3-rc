
# Polars Descriptive Statistics Analysis - week3

This Python module demonstrates the use of Polars for descriptive statistics analysis. The module reads a dataset from an Excel file, calculates summary statistics such as mean, median, and standard deviation, and visualizes the data distribution.

## Requirements

To run this module, you will need the following:

- Python 3.7
- Polars library
- Matplotlib
- Seaborn

You can install the required libraries using pip:

```bash
pip install polars matplotlib seaborn
```

## Usage

1. Clone this repository or download the code.
2. Ensure you have the required libraries installed.
3. Replace the `FILE_PATH` variable in the code with the path to your Excel file containing the dataset.
4. Run the script using Python:

```bash
python descriptive_statistics.py
```

The script will generate the following:

- Histogram of the data distribution
- Box plot of the data
- Kernel Density Estimation (KDE) plot
- Summary statistics including mean, median, and standard deviation


## Output

You can expect the script to produce visualizations and display summary statistics in the console.

![Histogram of Grades](histogram.png)

![Box Plot of Grades](boxplot.png)


```
Mean: 85.6
Median: 87.0
Standard Deviation: 8.3
```

