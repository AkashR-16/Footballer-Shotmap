# Footballer ShotMap

## Project Overview
Footballer ShotMap is a project designed to visualize the shot map of a specific football player. The project can generate shot maps for:
- Any player (e.g. for a specific match, season, or decade)
- Any team (e.g. for a specific match, season, or decade)

In this instance, the player analyzed is **Cristiano Ronaldo**, focusing on his European league career post-30 years old, covering his time at **Real Madrid, Juventus,** and **Manchester United**.

## Project Structure
The project consists of two main Jupyter Notebook files:
1. `scrape_understat.ipynb` - for scraping the required data
2. `Footballer_Shotmap.ipynb` - for generating the shot map visualizations

## Getting Started

### Step 1: Data Collection
1. **Source:** Data is sourced from [UnderStat](https://understat.com/).
2. **Scraping:** Run `scrape_understat.ipynb` to retrieve data for the selected player and timeframe.

### Step 2: Installation of Dependencies
1. Install `mplsoccer`, the main library used to create shot maps:
    ```bash
    pip install mplsoccer
    ```
2. Import the necessary modules and libraries in `Footballer_Shotmap.ipynb` to visualize the shot maps.

### Usage
Once the data is scraped and dependencies are installed, open `Footballer_Shotmap.ipynb` to generate the shot map visualizations based on your chosen criteria.

---


