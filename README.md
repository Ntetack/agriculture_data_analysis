# Agricultural Intelligence for Kenya Agricultural Research Institute (KARI)

##  Business Context

**Kenya Agricultural Research Institute (KARI)** is the leading agricultural research organization in Kenya, responsible for developing and promoting agricultural technologies to enhance food security and farmer livelihoods across the nation. Agriculture is the backbone of Kenya's economy, employing over 40% of the population and contributing significantly to GDP.

KARI has been collecting comprehensive data on crop production, weather patterns, and market prices across different counties in Kenya over several years. However, the institute faces critical challenges:

- **Seasonal Uncertainty**: Farmers need better guidance on optimal planting times and crop selection
- **Yield Prediction**: Inability to accurately forecast crop yields affects food security planning
- **Climate Variability**: Understanding the impact of rainfall and temperature on different crops
- **Market Volatility**: Price fluctuations make it difficult for farmers to plan and maximize profits
- **Resource Optimization**: Determining optimal fertilizer usage for different crops and conditions
- **Regional Variations**: Different counties have different agricultural potential and challenges


**Project goal:** Analyze time series data to uncover insights that can improve agricultural planning, enhance food security, and support farmer decision-making.

---

##  Dataset Description

You have been provided access to KARI's agricultural database in a CSV file named `kenyan_agriculture_data.csv` containing multi-year agricultural data across Kenyan counties.

### Data Fields:
- **Date**: Monthly timestamp of the observation
- **County**: Kenyan county (e.g., Nakuru, Kisumu, Meru, etc.)
- **Crop**: Type of crop (Maize, Wheat, Rice, Beans, etc.)
- **Yield_Tons**: Crop yield in metric tons
- **Rainfall_mm**: Monthly rainfall in millimeters
- **Temperature_C**: Average monthly temperature in Celsius
- **Price_KSH_per_kg**: Market price in Kenyan Shillings per kilogram
- **Area_Planted_Hectares**: Area planted in hectares
- **Fertilizer_Used_kg**: Amount of fertilizer used in kilograms