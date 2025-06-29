# Indonesia Earthquake Visualization with Leaflet in R

This project visualizes recent earthquake data in Indonesia using the **Leaflet** package in R. It uses publicly available GeoJSON data from the [USGS Earthquake API](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) and displays them on an interactive web map.

## Features

- Pulls earthquake data directly from the USGS API
- Filters data to only show events occurring in Indonesia
- Displays earthquake markers with custom icons
- Popups show location, magnitude, and time of each earthquake
- Hover labels for quick inspection
- Simple code with options for customization

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/sainsdataid/Leaflet-gempa-R.git
   ```

2. Open `Leaflet-gempa.Rmd` in RStudio.

3. Knit the R Markdown file to HTML.

## Requirements

Make sure you have these R packages installed:

```r
install.packages(c("leaflet", "sf", "httr", "jsonlite", "dplyr"))
```

## Preview

![screenshot](images/preview.png) <!-- Optional, replace with actual path -->

## Resources

- [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
- [Leaflet for R documentation](https://rstudio.github.io/leaflet/)

## Author

[Cahya Alkahfi](https://sainsdata.id)

📘 Tutorial in Bahasa Indonesia: [Visualisasi Data Gempa Bumi Indonesia dengan R](https://sainsdata.id/visualisasi-data/13317/visualisasi-data-gempa-bumi-indonesia-dengan-bahasa-r/)