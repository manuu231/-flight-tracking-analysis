# ADS-B Flight Analysis

## Overview

This project analyzes ADS-B (Automatic Dependent Surveillance–Broadcast) aircraft data using Python, DuckDB, Pandas, and Matplotlib. The goal is to explore flight activity, aircraft characteristics, altitude patterns, and speed distributions from real-world aviation data.

## Features

- Parse and process ADS-B JSON flight data
- Store and query large datasets using DuckDB
- Analyze frequently observed aircraft and flights
- Explore altitude and ground speed distributions
- Match aircraft information using ICAO databases
- Visualize aircraft type distributions
- Generate aviation traffic insights through data analysis

## Technologies Used

- Python
- Pandas
- DuckDB
- Matplotlib
- JSON

## Project Structure

```
├── adsb_mahal.ipynb
├── input_data/
├── basic-ac-db.json
├── README.md
└── requirements.txt
```

## Analysis Performed

### 1. Flight Data Processing
- Loaded ADS-B JSON files
- Extracted important flight attributes:
  - Aircraft Hex ID
  - Flight Number
  - Latitude & Longitude
  - Geometric Altitude
  - Barometric Altitude
  - Ground Speed

### 2. Aircraft Activity Analysis
- Identified most frequently observed aircraft
- Identified most common flight numbers

### 3. Altitude and Speed Analysis
- Examined aircraft altitude distributions
- Investigated relationships between altitude and speed

### 4. Aircraft Classification
- Matched aircraft records with ICAO databases
- Categorized aircraft by type
- Visualized aircraft type distributions

## Sample Insights

- Most active aircraft IDs in the dataset
- Most common flight numbers
- Aircraft type distribution
- Altitude and speed trends
- Traffic activity patterns

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/adsb-flight-analysis.git
cd adsb-flight-analysis
```

2. Install dependencies

```bash
pip install pandas duckdb matplotlib
```

3. Place ADS-B data files inside the `input_data` folder.

4. Run the notebook

```bash
jupyter notebook adsb_mahal.ipynb
```

## Dataset

This project uses ADS-B aircraft surveillance data containing aircraft positions, altitude, speed, and flight identifiers.

## Author

**Manpreet Mahal**
MS Applied Data Science
Clarkson University

## License

This project is intended for educational and research purposes.
