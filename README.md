# Florida Zip Codes Map with Highlights

This project generates a map of Florida's zip codes and highlights selected zip codes based on a given list. The map is created using GeoPandas and Matplotlib, with zip codes highlighted in green and others in white.

## Project Overview

The project uses a GeoJSON file containing Florida's zip code data and allows you to specify which zip codes to highlight. These zip codes are displayed on a map with a visual distinction, making it easy to see the specified areas.

### Features:
- Fetches Florida's zip codes GeoJSON from an online source.
- Allows the user to specify zip codes to be highlighted in green.
- Visualizes the data on a map using `GeoPandas` and `Matplotlib`.

## Requirements

Ensure you have the following Python libraries installed:

- `requests`
- `geopandas`
- `matplotlib`
- `json`

You can install these dependencies using `pip`:

```bash
pip install requests geopandas matplotlib
