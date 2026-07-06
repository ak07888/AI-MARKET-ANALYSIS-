# Project Title: Market Sentiment Analysis

## Description
This project focuses on analyzing market behavior by processing and interpreting financial datasets. The objective is to evaluate data relationships and identify patterns, such as identifying missing values and understanding dataset structures, to gain insights into market sentiment (e.g., Fear & Greed index).

## Technologies Used
* **Python**
* **Pandas** (Data manipulation and analysis)
* **NumPy** (Numerical computing)
* **Matplotlib** (Data visualization)
* **Google Colab** (Development environment)

## Key Features
* **Data Cleaning**: Pre-processing raw data to handle missing values and prepare it for analysis.
* **Exploratory Data Analysis (EDA)**: Examining dataset shapes, columns, and correlations between different financial indicators.
* **Insight Generation**: Identifying key trends in market data to support evidence-based conclusions.

## How to Run
1.  Ensure you have the required CSV files (`fear_green.csv` and `historical_trades.csv`) in the same directory as the notebook.
2.  Open the `.ipynb` file in **Google Colab** or a **Jupyter Notebook** environment.
3.  Run the cells sequentially to execute the data processing and visualization steps.

## Project Summary

### Methodology
* **Data Preprocessing**: The project involved cleaning two separate datasets—Fear & Greed Index and historical trade data—by identifying and handling missing values to ensure data integrity.
* **Data Analysis**: The datasets were merged and analyzed to evaluate the relationship between market sentiment (Fear & Greed) and trade volume.
* **Visualization**: Used `matplotlib` to plot and visualize the correlation between the indices and trade patterns to gain deeper technical insights.

### Insights
* **Sentiment Correlation**: Initial analysis reveals clear patterns where extreme shifts in the Fear & Greed Index correspond with specific fluctuations in trade frequency.
* **Data Completeness**: The analysis identified specific gaps in the historical trade data, which were successfully addressed during the cleaning phase to maintain accuracy.

### Strategy Recommendations
* **Refinement**: I recommend incorporating additional macroeconomic indicators (such as inflation rates or major market announcements) to further improve the predictive accuracy of the market sentiment model.
* **Automation**: The next step is to build an automated pipeline that pulls live data from APIs, allowing this analysis to run in real-time rather than relying on static CSV files.
