# Equity_Emphasis_Map
________________________________________

This project visualizes equity emphasis areas for residential solar deployment across the United States using geospatial data from the NREL STEADy (Solar for All Equity Data) tool. It highlights low-income communities and areas with viable residential solar potential, providing both static and interactive maps for exploration.
________________________________________

## 📌Features
________________________________________

  •	Geospatial Analysis with GeoPandas:
  
    o	Census tract-level filtering based on:
      	Median household income (bottom 25%)
      	Residential solar net present value (NPV)
      	Poverty rates
      	Justice40 (IRA_CEJST) and IRA Low-Income Community eligibility (IRA_LIC_C1)

      
  •	Static Maps:
  
    o	Continental US, Alaska, and Hawaii visualized separately with tract-level detail.
    
    o	State borders and tract outlines for clarity.
  
  •	Interactive Folium Maps:
  
    o	Hover tooltips display key equity metrics:
      	State and County names
      	IRA_LIC_C1 (%)
      	IRA_CEJST (%)
      	Poverty rate (%)
      	Median household income ($)
      
    o	Combined U.S. map (with repositioned Alaska and Hawaii for cartographic clarity).
________________________________________
# 🗂️ Data Sources

  •	NREL STEADy Tool:
    https://www.nrel.gov/state-local-tribal/steady.html
    (Shapefile download: includes tract-level socioeconomic, equity, and solar data.)
    
  •	U.S. Census TIGER/Line Shapefiles (for geographic context, optional)
________________________________________
# 🛠️ Tools & Libraries
  •	Python 3.10+
  •	GeoPandas
  •	Folium
  •	Shapely
  •	Matplotlib (for static maps)
  •	Pandas
________________________________________

# 👤 Author

Juan Segovia

•	LinkedIn: www.linkedin.com/in/juan-javier-segovia




