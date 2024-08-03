# Market Segmentation Based on Electric Vehicles

**Author:** Shashi Kumar Reddy Chintalapalli

## Overview

The electric vehicle (EV) industry is rapidly growing, driven by increasing demand for energy-efficient vehicles, environmental concerns, and the need to reduce carbon emissions. Machine learning is being utilized to improve the performance and efficiency of EVs, which can be segmented into:

- Battery Electric Vehicles (BEVs)
- Plug-in Hybrid Electric Vehicles (PHEVs)
- Hybrid Electric Vehicles (HEVs)

### Applications of Machine Learning in EVs

1. **Predictive Maintenance:** Analyzing vehicle data to predict when maintenance is needed, reducing breakdown risks and costs.
2. **Battery Management:** Optimizing battery performance by analyzing charge levels and temperatures to extend battery life.
3. **Route Optimization and Energy Management:** Using data on traffic patterns and weather to minimize energy consumption and emissions.

The global EV market is projected to reach $802.81 billion by 2027, growing at a CAGR of 22.6% from 2020 to 2027. However, challenges such as data standardization, high implementation costs, and the need for skilled professionals persist. 

## Problem Statement

The availability and accessibility of public charging stations for electric vehicles in Hawaii, specifically on the island of Oahu, are critical. The provided dataset includes information on five charging stations, highlighting a potential shortage of charging infrastructure. 

This shortage may hinder the adoption of electric vehicles in Hawaii, necessitating policies and initiatives to promote the installation of more public charging stations. Regular maintenance and upgrades of existing infrastructure are also essential to meet growing EV charging demands.

## Data Collection

The dataset from [data.hawaii.gov](https://data.hawaii.gov) includes:

- Location
- Zip code
- Facility type
- Charger location
- Station availability
- Number of chargers and ports
- Charger level
- Charge fee
- Manufacturer

This dataset serves as a valuable resource for understanding the public charging infrastructure in Hawaii. Users may need to preprocess the data to ensure its accuracy and gather additional data for a comprehensive analysis.

## Data Pre-processing

Data pre-processing is crucial for preparing the dataset for analysis. The following steps are involved:

1. Import necessary libraries: `numpy`, `pandas`, `seaborn`, and `matplotlib`.
2. Load the dataset and check for missing values.
3. Handle missing values by dropping unnecessary columns and filling remaining gaps with the mode.
4. Visualize the data to gain insights, such as plotting the number of charging stations by facility type.

## Data Visualization

Data visualization is vital for uncovering insights from the dataset. Libraries like Seaborn and Matplotlib can be used to create various visualizations:

- **Scatter Plots:** Display relationships between charger levels and availability.
- **Count Plots:** Show the distribution of charging station manufacturers.
- **Histograms:** Illustrate charge fee distributions.
- **Line Plots:** Show station availability trends.

Plotly can also be utilized for interactive visualizations, enhancing user engagement.

## Conclusion

This project aims to analyze the availability and accessibility of public charging stations for electric vehicles in Hawaii. By leveraging machine learning and data visualization, it seeks to provide valuable insights that can inform the development of EV infrastructure and policies in the state.

