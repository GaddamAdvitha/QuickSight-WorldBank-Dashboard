# Amazon QuickSight Dashboard Project

This project demonstrates how to build a comprehensive dashboard using **Amazon S3** and **Amazon QuickSight** with a dataset containing economic and social indicators. It focuses on visualizing trends, including **GDP**, **Unemployment**, **Life Expectancy**, **Infant Mortality**, and more.

## Overview

This project uses AWS services to create a set of visualizations from world economic data. The dashboard is hosted on **Amazon QuickSight**, while the dataset is stored in **Amazon S3**. This project aims to provide insights into global economic trends, visualizing metrics such as **GDP**, **Life Expectancy**, **Infant Mortality**, and **Electric Power Consumption**.

## Features

- **Economic Distribution Across Countries**: Shows how global wealth is distributed.
- **Total GDP Across Countries**: Summarizes the combined GDP of all countries.
- **Average Life Expectancy**: Highlights the average life expectancy across different countries and income groups.
- **Unemployment Trends**: Compares unemployment rates across income groups.
- **Correlation between Life Expectancy and Infant Mortality**: Visualizes the relationship between life expectancy and infant mortality across different regions.
- **Birth Rate vs. Death Rate Across Regions**: Compares birth and death rates globally.
- **Electric Power Consumption by Income Groups**: Displays the power consumption pattern among different income groups.

## Dataset

The dataset used in this project is provided by [World Bank](https://data.worldbank.org/), which contains various metrics related to world development indicators.

### Dataset Columns:

- **Country**: The name of the country.
- **Year**: Year of observation.
- **GDP**: The total Gross Domestic Product of the country.
- **GDP per Capita**: The GDP divided by the population.
- **Life Expectancy**: Average life expectancy in years.
- **Unemployment Rate**: The percentage of the population that is unemployed.
- **Birth Rate**: Number of live births per 1,000 people.
- **Death Rate**: Number of deaths per 1,000 people.
- **Electric Power Consumption**: The amount of power consumption (kWh per capita).

## AWS Services Used

### 1. **Amazon S3**
   - S3 is used to store the CSV dataset and manifest.json file.
   - The dataset is uploaded to an S3 bucket and linked to Amazon QuickSight.

### 2. **Amazon QuickSight**
   - Amazon QuickSight is used for building visualizations based on the uploaded dataset.
   - Various visualizations (bar charts, scatter plots, filled maps) are created to showcase the economic trends across countries.

## Project Setup

### Prerequisites:
- AWS account with access to **Amazon S3** and **Amazon QuickSight**.
- Basic knowledge of AWS services and data visualization.

### Steps to Recreate:

1. **Download the Dataset**:
   - Download the dataset from the World Bank or any other global economic dataset.

2. **Upload to Amazon S3**:
   - Create an S3 bucket and upload the dataset CSV file and `manifest.json` file.
   
3. **Configure the manifest.json**:
   - Update the `manifest.json` file with the correct S3 bucket name.

4. **Set Up Amazon QuickSight**:
   - Connect QuickSight to your S3 bucket by uploading the `manifest.json` file.
   - Import the dataset into QuickSight and start building your visualizations.

5. **Create Visualizations**:
   - Use QuickSight to create various charts such as **GDP Over Time**, **Life Expectancy vs. Infant Mortality**, and **Electric Power Consumption by Income Group**.


## Visualizations Included

- **Total GDP Across Countries**
- **Average GDP per Capita Comparison Across Income Groups**
- **Average Life Expectancy**
- **Mean Unemployment Across Nations**
- **Correlation Between Life Expectancy and Infant Mortality Rates**
- **Birth Rate vs. Death Rate Across Regions**
- **Electric Power Consumption Across Income Groups**

## How to Run

1. Make sure the dataset is properly uploaded to your **Amazon S3** bucket.
2. Use **Amazon QuickSight** to connect to the dataset.
3. Start creating visualizations and build your dashboard based on the metrics you want to explore.
4. You can further customize your dashboard to filter data by region, year, or income group.

## Useful Resources

- [Amazon QuickSight Documentation](https://docs.aws.amazon.com/quicksight/index.html)
- [World Bank Data](https://data.worldbank.org/)
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html)

## License

This project is licensed under the MIT License.

---

Happy building! 🚀

