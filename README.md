#Statistics Module Assignment: Telecom Dataset

## Overview

This repository contains my analysis of the "Mobile Phone Dataset," focusing on understanding the characteristics and pricing of various phone models. The project aims to explore relationships between phone features and their selling prices, using descriptive statistics and data visualization techniques.

## Dataset

The "Mobile Phone Dataset" includes information about various mobile phone models. It contains the following features:

* **PID:** A unique identifier for the phone model.
* **Blue:** Whether the phone has Bluetooth support (Yes/No or 1/0).
* **Wi_Fi:** Whether the phone has Wi-Fi support (Yes/No or 1/0).
* **Tch_Scr:** Whether the phone has touch screen support (Yes/No or 1/0).
* **Ext_Mem:** Whether the phone has external memory support (Yes/No or 1/0).
* **Px_h:** Number of pixels in the vertical axis of the phone.
* **Px_w:** Number of pixels in the horizontal axis of the phone.
* **Scr_h:** Height of the screen of the phone in centimeters (cm).
* **Scr_w:** Width of the screen of the phone in centimeters (cm).
* **Int_Mem:** Internal memory of the phone measured in megabytes (MB).
* **Bty_Pwr:** Maximum energy stored by the phone's battery measured in milli-Ampere-hours (mAh).
* **PC:** Resolution of the primary camera measured in megapixels (MP).
* **FC:** Resolution of the front camera measured in megapixels (MP).
* **RAM:** Random access memory available in the phone measured in gigabytes (GB).
* 
* **Depth:** Depth of the mobile phone measured in centimeters (cm).
* **Weight:** Weight of the mobile phone measured in grams (g).
* **Price:** Selling price of the mobile phone in rupees.

## Project Structure

## Tools and Libraries

* **Python:** Programming language used for analysis.
* **Pandas:** Data manipulation and analysis.
* **NumPy:** Numerical computing.
* **Matplotlib:** Data visualization.
* **Seaborn:** Advanced data visualization.
* **Jupyter Notebook:** Interactive coding and documentation environment.

## Analysis

The `mobile_phone_analysis.ipynb` Jupyter Notebook performs the following analyses:

1.  **Data Loading and Cleaning:**
    * Loading the "mobile_phone_data.csv" dataset using Pandas.
    * Handling missing values and data type conversions.
    * Addressing any data inconsistencies.

2.  **Descriptive Statistics:**
    * Calculating and interpreting measures of central tendency (mean, median, mode) and dispersion (standard deviation, variance) for numerical features.
    * Analyzing frequency distributions for categorical features.

3.  **Data Visualization:**
    * Creating histograms and kernel density plots to visualize the distribution of numerical variables.
    * Generating box plots to identify outliers and understand data spread.
    * Creating bar charts and count plots to analyze categorical variable distributions.
    * Visualizing relationships between variables using scatter plots and heatmaps, especially focusing on the relationship between phone features and price.

4.  **Correlation Analysis:**
    * Calculating correlation matrices to understand relationships between features, particularly how features correlate with 'Price'.

5.  **Feature Importance (Optional):**
    * If applicable, using techniques like feature importance from tree-based models to see which features impact price the most.

6.  **Interpretation and Insights:**
    * Drawing conclusions and summarizing key findings related to phone features and pricing.
    * Identifying potential factors that influence the selling price of mobile phones.

## Insights

From the analysis, the following insights were gained:

* [**Insert Insight 1: Example:** Higher RAM and camera resolution (PC, FC) are strongly correlated with higher phone prices.]
* [**Insert Insight 2: Example:** Screen size (Scr_h, Scr_w) and pixel resolution (Px_h, Px_w) show a positive correlation with price.]
* [**Insert Insight 3: Example:** Bluetooth and Wi-Fi are standard features, but their presence might not significantly impact price.]
* [**Insert any other significant insights here**]

## How to Run

1.  Clone this repository: `git clone [repository URL]`
2.  Navigate to the project directory: `cd [project directory]`
3.  Install the required libraries: `pip install pandas numpy matplotlib seaborn jupyter`
4.  Run the Jupyter Notebook: `jupyter notebook mobile_phone_analysis.ipynb`

## Learning Outcomes

Through this assignment, I have:

* Applied statistical methods to analyze a real-world mobile phone dataset.
* Strengthened my skills in data cleaning and preprocessing.
* Improved my ability to perform correlation analysis and interpret the results.
* Enhanced my data visualization skills to effectively communicate insights.
* Gained experience in extracting actionable insights from a product dataset.

## Contributing

Contributions are welcome. If you find any issues or have suggestions for improvements, please feel free to submit a pull request.
