# Climate Change Analysis of Nepal (GIS DATA)
## Assignment: GIS Data Science for Climate in Nepal

### Objective:
- The objective of this project is to analyze the climate change trends in Nepal, focusing on temperature and precipitation data. Using GIS data in both vector and raster formats, we will compute basic statistics, identify patterns, and visualize the climate data to gain insights into the changing climate in Nepal.


### Setup Instructions:

- Clone the repository from GitHub Classroom.
 ```bash
   git clone https://github.com/Omdena-NIC-Nepal/gis-data-science-assignment-sabinvankathmandu.git
   cd gis-data-science-assignment-sabinvankathmandu
   ```
- Ensure Python environment is set up with necessary libraries (e.g., pandas, geopandas, matplotlib, seaborn).
 ```bash
   pip install -r requirements.txt
   ```

### Data Collection and Preparation:

- For this assignment I have used the data listed here: https://github.com/Desmondonam/Nepal_Climate_change
    - This is the GIS data for Nepal for climate changes analysis and contains the vector and raster datas.

- Data Reading:
    - Vector Data: The vector data (e.g., district and province boundaries) has been loaded using geopandas.
    - Raster Data: The raster data (e.g., temperature and precipitation data for 2020 and 2050) has been loaded using rasterio.
    - Data Quality Check: The dataset was inspected for completeness and consistency. Missing values or potential issues were handled during data preprocessing.

### Data Visualization:

- Visualizations:
    - Temperature or Precipitation Trend Map: A map showing the trends in temperature or precipitation for Nepal, either for specific years (2020 vs. 2050) or across multiple time points. This allows for a visual representation of spatial patterns.

- Additional Visualizations:

    - Distribution Plots: Visualizing temperature and precipitation distributions for 2020 and 2050.
    - Comparative Bar Plots: Displaying mean, median, min, and max values of temperature or precipitation for comparison between years (e.g., 2020 vs 2050).
    - Exploratory Data Analysis (EDA):
        - Basic Statistics: The basic statistics for temperature and precipitation were computed :

            - Mean
            - Median
            - Minimum
            - Maximum
        - These values help in understanding the range and central tendency of the climate data.
    - Trends and Patterns: Visualizations and statistical summaries were used to identify climate patterns. Observations regarding the trends in temperature and precipitation changes, especially between 2020 and 2050, were noted.

    - Insights: Based on the analysis, insights into how the climate in Nepal is expected to change over time (e.g., increasing temperature, changing precipitation patterns) were summarized.

### Conclusion
- The analysis of climate trends in Nepal between 2020 and 2050 reveals significant changes in both temperature and precipitation patterns, indicating the growing impact of climate change. There is increase in mean and median temperature and precipitation from 2020 - 2050. Nepal is expected to experience warmer temperatures and more extreme precipitation patterns by 2050. While overall precipitation is projected to increase, the uneven distribution could lead to both droughts and severe floods, creating challenges for agriculture, water management, and disaster preparedness.

