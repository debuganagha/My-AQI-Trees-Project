# My-AQI-Trees-Project

## Overview
This project explores the relationship between tree cover and air quality in urban areas. By leveraging bioclimatic variables, air quality index (AQI) data, and spatial plant species information, the goal is to create a model that identifies areas where deforestation can be conducted with minimal negative impact on air quality. The system integrates environmental data, tree species characteristics, and spatial analysis to make informed recommendations for urban planning and deforestation decisions.

## Objective
The objective of this project is to develop a decision-making tool for identifying areas where tree removal or deforestation would have the least adverse effects on air quality. The model combines several factors, including:
- **Tree density and species importance**
- **Air quality measurements (AQI, PM2.5, NO2, CO)**
- **Geographical and bioclimatic data** (tried to include bioclimatic data, but faced issues)

By processing these inputs, the system aims to support responsible urban planning and tree removal strategies that help maintain ecological balance while considering factors such as air pollution and urban development.

## Features
- **Environmental Data Integration**: Combines AQI, tree density, species information, and bioclimatic variables to assess the impact of tree removal on air quality.
- **Clustering and Ranking Algorithms**: Uses clustering algorithms like DBSCAN to group tree locations and employs multi-criteria decision-making techniques (AHP and TOPSIS) to rank areas based on environmental impact.
- **Visual Mapping**: Provides visual representations of tree locations and their environmental impact, helping decision-makers identify permissible tree removal zones.
- **API Integration**: Retrieves real-time air quality data from APIs like OpenWeatherMap to update environmental factors dynamically.

## Methodology
1. **Data Collection**: 
   - **Spatial Plant Species Data**: Tree locations and species information are collected and processed.
   - **Air Quality Data**: Real-time AQI data is fetched through APIs such as OpenWeatherMap.

2. **Clustering**: 
   - DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is used to group tree locations based on proximity and environmental conditions.

3. **Ranking and Decision Making**: 
   - Techniques such as the Analytical Hierarchy Process (AHP) and Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) are employed to evaluate and rank potential areas for deforestation.

4. **Visualization**: 
   - A map-based interface is used to display tree locations, environmental conditions, and deforestation recommendations.

## Installation
To use this project, follow these steps:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/debuganagha/My-AQI-Trees-Project.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the necessary API keys for data access (e.g., OpenWeatherMap).
4. Run the main script to begin the analysis.

## Data Sources
- **GeoPlant Dataset**: Available at [GeoPlant Dataset](https://www.kaggle.com/datasets/picekl/geoplant/data?select=PA_metadata_train.csv)
- **OpenWeatherMap API**: Available at [OpenWeatherMap API](https://openweathermap.org/)

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Suggestions for improvements and new features are welcome.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Special thanks to [GeoPlant Dataset](https://www.kaggle.com/datasets/picekl/geoplant/data?select=PA_metadata_train.csv) for providing the spatial plant species data.
- Thanks to [OpenWeatherMap API](https://openweathermap.org/) for providing air quality data through their API.

## Contact
For any questions or feedback, feel free to contact me at [anaghabhavaraju@gmail.com].
