## Aviation Analysis
### Overview:
This project involves analyzing aviation accident and incident data with over *88,889 records* to derive actionable insights for safety and operational improvements.

### Key Highlights:
1. *Data Cleaning:*
   - Processed missing values for columns like Latitude, Longitude, and Airport Name.
   - Standardized missing values to "UNKNOWN" and removed duplicates.
   - Ensured data consistency by converting numeric fields to appropriate data types.

2. *Insights:*
   - *Weather Conditions:* VMC (Visual Meteorological Conditions) accounted for *77,303 cases*, indicating the most common weather condition during accidents.
   - *Flight Phase:* Landing (*15,428 cases*) was identified as the most accident-prone phase of flight.
   - *Airport Analysis:* Airports like Merrill Field and Van Nuys reported the highest accident frequencies after private airports.

3. *Visualizations:*
   - Correlation heatmaps to explore weather and injury severity.
   - Bar plots for accident frequency by airport, phase of flight, and weather conditions.

### Tools & Technologies:
- *Python*: Pandas, NumPy, Seaborn, Matplotlib.
- *Data Source:* AviationData.csv
