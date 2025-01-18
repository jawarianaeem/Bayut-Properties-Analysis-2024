# Bayut-Properties-Analysis-2024

## Description
This report analyzes a dataset consisting of 41,381 property listings located in the UAE. The dataset contains information about the properties' selling prices, type, location, furnishing status, and various other attributes. The objective of this analysis is to understand the characteristics of the property market in UAE, including the distribution of prices, types of properties available, and other significant factors that affect property listings.

## Data Overview
The dataset comprises 22 attributes, including details such as price, property type (e.g., Apartment, Townhouse), number of bedrooms and bathrooms, geographical coordinates, and other property-related information. An initial inspection showed no missing values in the key columns. However, some geographical coordinates were missing and were excluded to maintain the integrity of the spatial analysis.

## Data Cleaning and Preprocessing
To prepare the dataset for analysis, the following steps were performed:

- Handling Missing Values: Records with missing geographical coordinates were removed to ensure all properties could be accurately mapped if needed.
- Removing Duplicates: The dataset was checked for duplicates to maintain data integrity, with no duplicates identified.
- Outlier Detection and Removal: Outliers in the price column were identified using the Interquartile Range (IQR) method and excluded to concentrate on typical market conditions.

## Exploratory Data Analysis (EDA)

- Price Distribution:
The analysis revealed a right-skewed price distribution, indicating that the majority of properties fall within the lower to mid-range price segment, with fewer high-priced properties. The mean price was calculated and visualized using a histogram.

- Property Types and Sizes:
The dataset was analyzed to examine the prevalence of different property types and their characteristics, such as the number of bedrooms, bathrooms, and parking spaces.

- Geographical Insights:
Properties were mapped using latitude and longitude data to identify areas with high property density and potential real estate market hotspots.


## Visualization

- Histograms and Box Plots:
Histograms were utilized to display the distribution of prices and the number of bedrooms and bathrooms in the dataset. Box plots provided a clear view of data spread and helped identify outliers.

- Heatmaps:
A heatmap was generated to show the concentration of properties across various areas, highlighting popular and high-demand locations.

# Conclusions
The analysis revealed key insights into the UAE property market:

- Market Characteristics:
The market is diverse, offering properties across a spectrum from budget-friendly to luxury options. Price trends suggest that the market caters to a broad range of buyers.

- Popular Locations:
Specific areas in Dubai and Abu Dhabi exhibit a higher concentration of listings, indicating greater demand and potentially higher property values in these regions.

- Recommendations for Stakeholders:
Investors and Realtors: Focus on high-demand areas for potential buying opportunities.
Sellers in Less Dense Areas: Consider adjusting pricing strategies to align with current market conditions.

I also design Dashboard in tablaue which covers some questions 
-Total Number of listing on Bayut 
-Average Price by Property Type
-Total Properties for Sale
-Average Price by City
-Price trends for properties across cities or Areas
- How furnishing status affects property price 

You can find image below of dashboard
<img width="1264" alt="Screenshot 2025-01-18 at 17 28 16" src="https://github.com/user-attachments/assets/0c41af1f-5193-457a-85de-54a22107bf0c" />









