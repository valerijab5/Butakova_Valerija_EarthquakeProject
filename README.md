# Earthquake Data Analysis — ESC 113

## Objective
Analyze global earthquakes of magnitude 4.0 or greater from October 1–31, 2026 (UTC), using Python and the USGS Comprehensive Earthquake Catalog (ComCat). This project examines earthquake magnitude, depth, frequency, and potential engineering relevance.

## Files
- `Earthquake_Analysis.ipynb` — Python analysis, four figures, interpretations, and automatic report generation.
- `Project_Report.docx` — report generated from actual dataset results after running the notebook.
- `earthquakes.csv` — unchanged USGS data downloaded by the notebook.
- `01_magnitude_histogram.png` through `04_depth_categories.png` — analysis figures.

## How to run
1. Open `Earthquake_Analysis.ipynb` in Google Colab.
2. Choose **Runtime → Run all**. Internet access is required to download USGS records.
3. The notebook displays data checks, statistics, classifications, four plots, and interpretations.
4. The last cells generate `Project_Report.docx` and download the report, CSV, and plots.

## Data source
USGS ComCat FDSN Event API:
https://earthquake.usgs.gov/fdsnws/event/1/query?format=csv&starttime=2026-10-01&endtime=2026-11-01&minmagnitude=4&orderby=time

Records can be revised by USGS. The dataset excludes earthquakes smaller than magnitude 4.0, so its counts do not represent all earthquakes worldwide.

## Engineering relevance
The analysis identifies stronger, shallower events for follow-up review. Actual damage depends on ground motion, distance, soil conditions, and the vulnerability of exposed structures. See the report and notebook outputs for numerical findings.
