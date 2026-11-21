# Dhaka AQI Tracker

A single-page web app that tracks live air quality across Dhaka. It shows the current US Air Quality Index (AQI) in a large circular gauge whose colour and the page background shift with the air-quality category, along with PM2.5 and PM10 readings, today's hour-by-hour AQI chart, and the worst AQI of each of the past 7 days. Switch between Dhaka, Uttara, Mirpur, Gulshan, Motijheel, Old Dhaka and Savar to compare areas.

**Live demo: https://nafiz-xd.github.io/dhaka-aqi-tracker/**

## Features

- Big circular AQI gauge — ring colour matches the US AQI category and fills in proportion to the AQI value
- Plain-language health advice for each category, from Good to Hazardous
- Current PM2.5 and PM10 readings (µg/m³) as stat chips
- Today's hourly AQI chart, with each bar coloured by its category
- Last 7 days strip — the maximum AQI for each of the past 7 days
- Area presets for Dhaka, Uttara, Mirpur, Gulshan, Motijheel, Old Dhaka and Savar
- Page background gradient that shifts with the current AQI category
- Last-updated time, Refresh button, loading state and a clear error state if data cannot be loaded
- Fully responsive, works on a 360px phone screen with no horizontal scrolling

## Tech

- Single `index.html` — vanilla HTML, CSS and JavaScript, no build step and no dependencies
- Open-Meteo Air Quality API / CAMS (Copernicus Atmosphere Monitoring Service) — free and keyless
- Values are approximate for each area, from the CAMS model grid (~10 km), not street-level sensors

---
Built by Nafiz Bin Azad
