# NYC-311-Noise-Analysis
## Overview

This project retrieves, analyzes, and visualizes 311 "Noise" service request data from the NYC Open Data API. It covers:

- Data Retrieval: Pulls the most recent 1,000 noise-related complaints from the last 30 days (You can pull more then 1000 if you decide to)

- Data Exploration: Inspects dataset structure, handles missing values, and identifies the top noise complaint descriptors.

- Insights Generation: Summarizes which boroughs report the most complaints and how complaint types vary by borough.

- Visualizations: Produces a suite of charts (bar, horizontal bar, heatmap, pie, bubble) to highlight spatial and descriptor-level patterns.

## Key Sections in the Notebook

1. Part 1: API Query – Defines noise_complaints() to fetch the data.

2. Part 2: Exploration – Uses noise_data() to inspect shape, handle missing values, and summarize the top descriptors.

3. Part 3: Insights – Implements noise_by_boroughs() to aggregate counts by borough and descriptor, with written observations.

4. Part 4: Visualizations – Calls build_visualization() to render five charts, each accompanied by an interpretation.

## Data Source
- NYC Open Data: 311 Service Requests (Resource ID: erm2-nwe9)*
- API Endpoint: https://data.cityofnewyork.us/resource/erm2-nwe9.json*
