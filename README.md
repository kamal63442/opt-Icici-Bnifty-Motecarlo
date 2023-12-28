# Notebook Name: `analyze_option_data.ipynb`

## Overview

This Jupyter Notebook performs the following tasks:

1. Connects to an SQLite database (`option_history.db`).
2. Retrieves data from multiple tables in the database and organizes it into a dictionary of Pandas DataFrames (`option_price_df`).
3. Displays information about the retrieved data, including the number of keys, columns, and indices for each DataFrame.
4. Uses Plotly to create a line plot of close prices for a specific expiry date (`19-JAN-2023`).

## Usage

1. Ensure that you have the required Python libraries installed:

    ```bash
    pip install pandas plotly sqlite3
    ```

2. Run the Jupyter Notebook (`analyze_option_data.ipynb`).

3. View the output, which includes information about the database, DataFrame contents, and a Plotly plot.

## Files

- `option_history.db`: SQLite database containing option data.
- `analyze_option_data.ipynb`: Jupyter Notebook script for analyzing and visualizing option data.
- `read.md`: This README file.

## Dependencies

- Python 3.x
- Pandas
- Plotly
- SQLite3

## Notes

- Make sure to update the `expiry_date_to_plot` variable if you want to analyze a different expiry date.

---

Copy and paste this template into a `read.md` file in the same directory as your Jupyter Notebook. Feel free to customize it further based on your specific needs and details about the data and analysis in your notebook.
