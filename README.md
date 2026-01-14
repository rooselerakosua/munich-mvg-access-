
# Public Transport Accessibility in Munich (150 m)

## Objective
This project analyzes how much of Munich’s population is served within a very close walking distance (150 meters) of MVG public transport stops.

## Data
- MVG public transport stops (Munich Open Data)
- Population by Stadtbezirksteil, December 2017
- Administrative boundaries of Munich Stadtbezirke

## Methodology
1. Reprojected all spatial layers to ETRS89 / UTM Zone 32N
2. Buffered MVG stops by 150 meters
3. Intersected buffers with Stadtbezirk boundaries
4. Calculated population served proportionally based on intersected area
5. Aggregated population served by Stadtbezirk
6. Visualized results using graduated choropleth mapping

## Output
![Population served within 150 m](outputs/map_population_served_150m_munich.png)

## Tools
- QGIS
- Munich Open Data

## Author
Your Name
