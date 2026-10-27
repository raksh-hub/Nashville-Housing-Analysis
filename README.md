# Nashville Housing Analysis Dashboard

A data analysis project using **MySQL and Power BI** to analyze Nashville housing sales, pricing, property characteristics, and locations.

![Nashville Housing Dashboard](dashboard-preview.png)

## Data Cleaning & Preparation

The raw Nashville Housing dataset was cleaned using **MySQL**, including:

- Converting and formatting sale dates
- Standardizing inconsistent values
- Handling missing property addresses
- Cleaning and converting sale prices
- Splitting property and owner addresses
- Removing duplicate records
- Removing unnecessary columns

The cleaned data was then imported into **Power BI**, where **Power Query and DAX** were used to create calculated fields, sales price and acreage brackets, and KPI measures.

## Dashboard

The dashboard analyzes:

- Total properties sold and total sales value
- Sales trends by year and month
- Sales price brackets
- Average sale price by bedrooms and land use
- Sales by acreage
- Sale price vs. acreage
- City-level sales activity

Interactive **Year, City, and Sale Price Bracket** slicers allow users to explore the data.

## Key Insights

- **56K+ properties** are included in the dataset.
- Total recorded sales are approximately **$18.46 billion**.
- Most sales fall within the **$100K–$500K** price range.
- Sale prices vary across property types and cities.
- Most properties are under **2 acres**.

## Tools

**MySQL | Power BI | Power Query | DAX**

## Dataset

**Source:** [Kaggle — Nashville Housing Data](https://www.kaggle.com/datasets/tmthyjames/nashville-housing-data)
