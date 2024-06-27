# Croatian Earthquakes Dashboard

This dashboard provides an interactive visualization of earthquakes in Croatia from 1990., sourced from the United States Geological Survey (USGS).

## Features

- Interactive map showing earthquake locations
- Filterable data table of earthquake events
- Real-time data updates from USGS
- Responsive design for various screen sizes

## Data Source

The earthquake data is sourced from the [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/). The data is updated daily at 9:00 AM UTC.

## Technologies Used

- [Quarto](https://quarto.org/) for creating the dashboard
- [Observable JS](https://observablehq.com/) for interactive visualizations
- [Leaflet](https://leafletjs.com/) for mapping
- [R](https://www.r-project.org/) for data processing

## Local Development

To run this dashboard locally:

1. Clone this repository
2. Install [Quarto](https://quarto.org/docs/get-started/)
3. Install R and the required packages (tidyverse, httr2, sf)
4. Run `quarto preview` in the project directory

## Deployment

This dashboard is automatically updated and deployed daily at 9:00 AM UTC using GitHub Actions.

## Contributing

Contributions to improve the dashboard are welcome. Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- USGS for providing the earthquake data
- OpenStreetMap contributors for map data

## Contact

For any queries regarding this project, please open an issue on this repository.
