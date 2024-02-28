# New York Housing Prices Analysis

## Overview
This project aims to analyze housing prices in New York using real estate data obtained from a dataset. The analysis involves exploring various aspects of the dataset such as price distribution, correlation between price and property size, geographical distribution of prices, and more.

## Requirements
- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Plotly

## Installation
1. Clone this repository to your local machine.
2. Ensure Python 3.x is installed on your system.
3. Install the required libraries using pip:
    ```
    pip install numpy pandas matplotlib seaborn plotly
    ```

## Usage
1. Run the Python script `housing_analysis.py`.
2. The script will load the dataset, perform data analysis, and generate visualizations.
3. Results will be displayed in the console and saved as image files in the current directory.

## Dataset
The dataset used in this project (`NY-House-Dataset.csv`) contains information about various properties in New York, including details such as price, number of bedrooms and bathrooms, property size, address, and geographical coordinates.

## Analysis Steps
1. Data Loading and Overview:
   - Load the dataset using Pandas.
   - Display basic information about the dataset (columns, data types, etc.).
   - Check for missing values.

2. Data Preprocessing:
   - Remove outliers to focus on main price ranges.

3. Exploratory Data Analysis:
   - Scatterplot comparing prices by sublocality.
   - Visualization of prices on a map.
   - Heatmap showing correlation between price and property size.
   - Boxplot displaying the interquartile range (IQR) of property prices based on the number of bedrooms.

4. Interpretation:
   - Analyze findings from visualizations to draw insights about housing prices in different areas of New York.

## Results
- The analysis provides insights into housing price distribution, correlation with property size, and geographical variations across different sublocalities in New York.

## Contributors
- krsnathkr

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
