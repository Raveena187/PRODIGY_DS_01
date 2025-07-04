# DATA VISUALISING
# Objective:
The objective of this project is to analyze and visualize the distribution of a categorical or continuous variable.
# Technologies Used:
Programming Language: Python
Libraries: pandas, matplotlib
Platform: Jupyter Notebook

# Methodology:
Data Import & Cleaning:
    The CSV file was read using pandas.read_csv() with a skiprows=4 parameter to bypass metadata.
    Unnecessary columns (Indicator Name, Indicator Code) were removed.
User Interaction:
    The user is prompted to input a country name.
    For population growth, starting year and ending year is prompted.
Visualization:
    A bar chart is plotted:
        X-axis: Years (1960 to most recent year)
        Y-axis: Population (converted to millions for readability)
    A histogram is plotted:
        X-axis: Growth Rate (%) across all countries
        Y-axis: Number of countries in each bin

# Insights: 
Countries show significant diversity in population dynamics.

Bar charts give a detailed view of a single country’s growth.

Histograms reveal global trends, such as:

    Countries with negative or near-zero growth.

    High-growth developing nations.

# Conclusion:
This project offers a powerful yet simple way to visualize both long-term population trends for individual countries and the global distribution of growth.