# 🏅 Olympic Data Analytics Pipeline

## End-to-End Data Engineering Project

This project implements a comprehensive data engineering pipeline to analyze historical Olympic Games data, uncovering insights into host country advantage, medal conversion efficiency, comeback stories, and sports dynasties.

🔗 [View Interactive Dashboards on Tableau Public](https://public.tableau.com/views/OlympicDataAnalyticsProject/Home?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Olympic Analytics Pipeline](images/architecture-diagram.png)

## Project Overview

This project transforms raw Olympic historical data into interactive analytical dashboards through a modern cloud-based data engineering pipeline. The solution leverages Azure Data Lake Storage, Azure Databricks, Azure Synapse Analytics, and Tableau to deliver powerful sports performance insights.

The analysis focuses on four key areas:
- **Host Country Performance Dynamics**: Quantifying the "home field advantage" phenomenon
- **Medal Conversion Efficiency**: Identifying which countries are most efficient at converting participants to medals
- **Longest Gaps & Comebacks**: Revealing surprising medal drought comebacks across Olympic history
- **Medal Dynasties**: Discovering long-term dominance patterns in specific sports

The pipeline demonstrates an industry-standard approach to data engineering, from ingestion through transformation and analysis to visualization.



## Technology Stack

### Azure Data Lake Storage Gen2
- Served as the primary data storage layer
- Provided hierarchical namespace for efficient data organization
- Enabled secure access to raw and transformed data

### Azure Databricks
- Utilized for large-scale data transformation
- Leveraged PySpark for distributed data processing
- Implemented complex transformations like time-gap analysis and medal calculations

### Azure Synapse Analytics
- Provided serverless SQL pool capabilities
- Created external tables connecting directly to data lake
- Developed analytical views for specialized Olympic analyses

### Tableau
- Created interactive dashboards for data visualization
- Implemented filters and parameters for user-driven exploration
- Published visualizations for public sharing

![Technology Stack Overview](images/tech-stack.png)


## Key Insights

### Host Country Performance
- Countries experience an average 30-50% increase in medal count when hosting the Olympics
- Some countries show a post-host "hangover" with performance dropping after hosting
- Certain sports show a stronger home-field advantage than others

### Medal Conversion Efficiency
- Smaller countries with specialized sports programs often show higher conversion rates
- Converting participants to medals has become more competitive over time
- Top conversion rates are often seen in countries with targeted sports investment

### Longest Gaps & Comebacks
- Several countries have returned to medal success after gaps exceeding 20 years
- Comeback patterns often coincide with national sports development initiatives
- Certain sports show more volatility in medal patterns than others

### Olympic Dynasties
- Identified 15+ countries with dynasties spanning 5+ consecutive Olympics
- Swimming, athletics, and wrestling show the most pronounced dynasty patterns
- Political and economic factors often influence the rise and fall of Olympic dynasties
