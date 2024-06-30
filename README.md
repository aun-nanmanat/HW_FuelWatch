# Data Science Concepts: Analysis of Fuel Prices Over Time in Western Australia

## Data

[Fuel Watch](https://www.fuelwatch.wa.gov.au) is a fuel monitoring service created by the Government of Western Australia. It provides information about fuel prices at the various petrol stations in Western Australia.
Historical fuel prices are provided in monthly chunks on the website https://www.fuelwatch.wa.gov.au/retail/historic. On this site you find links to csv-files with the data. Data files are stored at URLs of the following form `https://warsydprdstafuelwatch.blob.core.windows.net/historical-reports/FuelWatchRetail-MM-YYYY.csv`. 

## Objective:
To analyze fuel prices in Western Australia over the last 12 months using data from the FuelWatch service, focusing on price trends, regional variations, and the impact of external factors.

## Key Techniques and Methodologies:
- **Data Extraction and Preprocessing:** Utilized data from FuelWatch, covering variables such as publish date, trading names, brand description, product price, location, and region. Cleaned and prepared the data for analysis.

- **Data Visualization:** Created various visualizations including bar plots and line plots to illustrate the distribution of data points, average price trends, and regional variations over time.

- **Exploratory Data Analysis (EDA):** Conducted in-depth EDA to identify patterns and trends in fuel prices across different brands, regions, and specific areas within regions.

## Key Findings:
- **Price Spikes and Rapid Drops:** Identified occasional price spikes followed by rapid drops, primarily influenced by global crude oil prices, geopolitical events, and changes in government taxes or regulations.

  - Example: In July 2023, OPEC+ extended oil production cuts, leading to a notable increase in fuel prices.

- **Regional Price Variations:**

  - **Higher Prices in Remote Areas:** Remote regions such as Kimberley showed significantly higher average fuel prices due to increased transportation and distribution costs.

  - **Urban vs. Rural:** Urban areas exhibited more competitive pricing, leading to lower average prices compared to remote or less competitive regions.

- **Competition Among Fuel Retailers:**

  - **Impact on Prices:** Areas with more fuel retailers, such as Mandurah and Murray, had lower average prices due to higher competition.

  - Conversely, areas like Waroona, with fewer competitors, exhibited higher prices.

- **Unique Pricing Strategies of Petrol Stations:**

  - **Consistent Pricing:** The Canal Shop maintained a stable pricing strategy with minimal fluctuations, likely to attract and retain customers through price stability.

  - **Competitive Pricing:** Liberty Pinjarra consistently offered lower prices compared to other stations, indicating a competitive approach to gain market share.

- **Data Visualization Insights:**

  - **Bar Plots:** Illustrated the distribution of data points among different brands and regions, highlighting areas with dense or sparse data coverage.

  - **Line Plots:** Showed average price trends over time, providing a clear view of how prices evolved in different regions and for different brands.

## Conclusion:
The analysis provided valuable insights into the factors influencing fuel prices in Western Australia, including external market forces, regional dynamics, and competition among retailers. The findings can inform policy decisions and strategic planning for fuel distribution and pricing strategies.
