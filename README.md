# GeoRoute 🌍

## Overview

GeoRoute is a Python tool that combines the power of traceroute and geolocation to visualize the journey of your network packets as they travel from your device to a destination host or IP address. By mapping out the route and providing location data for each hop, GeoRoute offers a unique perspective on network diagnostics.

## Features

### 1. Traceroute Analysis

- **Visualize the Path**: Trace the route that your network packets take through different hops.

- **Hop Details**: Obtain information about each hop, including hostnames and response times.

### 2. Geolocation Data

- **City, Region, Country**: Discover the location of each hop, complete with city, region, and country information.

- **Interactive Map**: View the entire route on an interactive map for a dynamic visual experience.

### 3. User-Friendly Interface

- **Custom Icons**: Each hop is marked with a unique icon, making it easy to distinguish between locations.

- **Map Export**: Save the route map as an HTML file for future reference.

## Getting Started

1. Run the script using `python GeoRoute.py` in your terminal.

2. Enter the destination host or IP address you want to trace.

3. Customize the maximum number of hops, hop timeout, and whether to display the route map.

4. GeoRoute will provide a visual map of the route with geolocation data for each hop.

## Requirements

- Python 3.x
- Required Python packages (install via `pip`):
  - `requests`
  - `folium`
  - `scapy`

## Usage

- Explore the network path to a destination.
- Discover the location of each hop in the route.
- Use the interactive map for a dynamic visualization.
- Customize settings to tailor your analysis.



🌐 **Explore Your Network's Journey with GeoRoute!** 🚀
