# Weatherville

A customizable weather map that runs entirely in the browser from free, keyless data feeds. One file, no build step, no backend.

**Live:** https://unclestev.github.io/Weatherville/ (after GitHub Pages is turned on: Settings → Pages → Deploy from branch → `main` / root)

## Features
- Eight base maps, with place names drawn above the weather
- Radar loop: US NEXRAD (5-minute frames) or RainViewer worldwide
- GOES / VIIRS satellite, US warning polygons, a grid of model values across the map
- Current conditions, draggable hourly charts, 7–16 day outlook, air quality, US alerts
- Choice of weather model, units, tiles, charts, theme, saved places, copy/paste settings backup

## Data sources
| Purpose | Feed |
|---|---|
| Forecast, air quality, place search | [Open-Meteo](https://open-meteo.com/) (CC BY 4.0, free for non-commercial use) |
| US radar | [Iowa Environmental Mesonet](https://mesonet.agron.iastate.edu/) NEXRAD tiles |
| Global radar | [RainViewer](https://www.rainviewer.com/) (personal use, attribution required) |
| Satellite | [NASA GIBS](https://earthdata.nasa.gov/gibs) |
| Alerts | [US National Weather Service](https://www.weather.gov/documentation/services-web-api) |
| Base maps | Esri, OpenStreetMap contributors, OpenTopoMap, USGS |
| Reverse place names | BigDataCloud |

## Run locally
Serve the folder with any static server, for example `python3 -m http.server`, and open `http://localhost:8000`.
