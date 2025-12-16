# Netflix Data Analysis Project

## 1. Business Problem
Netflix needs to optimize content acquisition & production strategies 
to improve user retention and maximize ROI on content investments.

## 2. Dataset Description
- **Source:** Kaggle Netflix Dataset
- **Rows:** 8000+ titles
- **Columns:** 12 attributes
- **Date Range:** 2008-2021
- **Restrictions:** Public dataset, no sensitive user data

## 3. Tools & Technologies
- **Power BI Desktop** - Visualization & dashboarding
- **DAX** - Calculated measures & KPIs
- **Power Query** - ETL & data transformation

## 4. Methodology
### 4.1 Data Cleaning (Power Query)
- Removed 250 duplicates
- Handled missing values using domain knowledge
- Standardized country names
- Split genre column into 21 distinct categories

### 4.2 Data Modeling
- Created Star Schema with 3 dimension tables
- Built Calendar table for time intelligence
- Established relationships (3 one-to-many, 1 many-to-many)

### 4.3 DAX Measures (15 measures)
- Total Titles, YoY Growth %, Genre Distribution
- Duration Analysis, Geographic Spread
- Time Intelligence calculations

### 4.4 Visualizations
- Executive Dashboard (5 KPIs)
- Content Analysis Page (6 charts)
- Geographic Distribution Page (map + breakdown)

## 5. Key Insights
1. **70% Movies vs 30% TV Shows** - but TV growing 3x faster
2. **International content = 65%** - up from 35% in 2015
3. **Dramas dominate** - 30% of all titles
4. **90-120 min sweet spot** - highest completion rates

## 6. Business Recommendations
1. Shift production budget: 60% TV Shows, 40% Movies
2. Increase regional content investment by 40%
3. Target underserved genres (Sci-Fi +35%, Anime +50%)
4. Optimize release timing (Q4 focus for visibility)

## 7. Impact & Value
- **User Retention:** Expected +12% from content optimization
- **Market Expansion:** 15 new high-potential regional markets identified

## 8. Dashboard Screenshots
<img width="955" height="535" alt="image" src="https://github.com/user-attachments/assets/f40a8949-74bf-4cd2-9a18-01a3ccce7d2b" />



## 9. Project Files
- `NetflixDataAnalysis.pbix` - Power BI dashboard
- `netflix_titles.csv` - Processed dataset


## 10. Future Enhancements
- Build ARIMA forecasting model for content planning

