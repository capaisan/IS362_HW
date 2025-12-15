# IS 362 Final Project Proposal

## Analyzing US Employment Trends and Economic Indicators

**Motivation:**
Understanding job market trends and economic health is crucial for making informed career decisions and understanding the broader economy. This project aims to analyze US employment data and economic indicators to identify patterns of economic downturns, job market changes, and sector-specific trends. By examining unemployment rates, job growth across different industries, and key economic indicators like GDP, we can gain insights into how the US economy has evolved over recent years and identify periods of economic stress or growth.

**Data Sources:**
1. **FRED API (Federal Reserve Economic Data)**: We will retrieve unemployment rate data, GDP data, and other economic indicators. FRED provides a reliable, free API with extensive economic time series data.
2. **Bureau of Labor Statistics (BLS) API**: We will use this to gather employment data by industry sector to analyze which sectors are growing or declining.

**Workflow:**
1. **Data Acquisition**: Connect to FRED and BLS APIs to download relevant datasets (unemployment rates, GDP, employment by sector)
2. **Data Cleaning & Transformation**: Convert date formats, handle missing values, reshape data for analysis, and merge datasets
3. **Analysis**: Calculate statistical summaries, identify trends over time, perform correlation analysis between unemployment and GDP, and group data by industry sectors
4. **Visualization**: Create line charts showing trends over time, bar charts comparing sectors, and interactive visualizations to explore the data
5. **Conclusions**: Identify key economic downturns, analyze which sectors were most affected, and draw conclusions about overall economic health

The project will demonstrate proficiency in working with APIs, data transformation using pandas, statistical analysis, and creating meaningful visualizations to support data-driven conclusions.
