# Egypt Red Sea Earthquake Analysis (1955-2024)

## Overview
Analysis of earthquake activity in Egypt's Red Sea region over a 70-year period, examining patterns in frequency and magnitude over the years.

## Dataset
- **Source**: [Kaggle - Egypt Red Sea Earthquake Dataset](link)
- **Time Period**: 1955 to 2024
- **Records**: 427 earthquakes
- **Key Variables**: Date, magnitude, latitude, longitude, depth

## Project Goals
1. Identify the years with the most earthquake activity
2. Look at the earthquake activity (quantity and strength) over the whole period 1955 to 2024
3. Identify the relationship (if any) between the earthquake strength and focal depth

## Key Findings

### 1. Peak Activity in the 1990s
- **1995 experienced the highest number of earthquakes (110 events)**
- The 1990-2000 decade saw a dramatic increase in recorded earthquakes (369 total)
- This spike likely reflects either improved monitoring technology, or an actual increased activity.

### 2. Strongest Earthquake
- **Magnitude 7.2 earthquake in 1995**
- Top 15 strongest earthquakes range from 5.5 to 7.2 magnitude
- Majority of the strongest earthquakes each year fall mainly in the micro to moderate area - 4 to 6 Mw

Scale:
    2 Mw - micro,
    5 Mw - moderate,
    7 Mw - major,
    9+ Mw - great

### 3. Consistent Magnitude Patterns
- Average earthquake magnitude remains steady around 4.5-6.5 throughout the 70-year period
- No clear trend of increasing earthquake strength over time

### 4. Depth Patterns
- No clear pattern between depth and magnitudes
- Deepest recorded earthquake reached 35 km, with a magnitude of 4.3 Mw
- Strongest earthquake (7.2 Mw) had a depth of 10 km

## Visualizations
- Earthquake frequency by decade
- Magnitude trends over time
- Depth trends over time

## Technologies Used
- **Python 3.13.5**
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Numpy** - Data visualization

## Technologies Used but abandoned midway:
- **Folium** - Interactive mapping
- **Geopy** - Reverse geocoding (coordinates to location names)

## How to Run
1. Clone the repository
2. Install required packages: `pip install pandas matplotlib`
3. Open `earthquake_analysis.ipynb` in Jupyter Notebook or VS Code
4. Run all cells

## Files
- `RedSea_Earthquake_Analysis.ipynb` - Main analysis notebook
- `README.md` - Project documentation

## Author
Noha Khaled

## Future Improvements
- Compare Red Sea earthquakes with other regions in Egypt
- Compare Red Sea earthquakes during the peak in the 90s with other regions in the World
- Analyze correlation between the rms and recorded magnitudes and depths