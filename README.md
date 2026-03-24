# Capstone-Project-Ashtree-Marine

## Objective

This project analyses and visualises competitive sailing telemetry data from Ashtree Marine’s Rockit Analytics Platform to improve how performance data is presented. The goal is to reduce visual clutter and enable clear comparison across multiple sessions and boats, helping users extract fast, actionable insights from complex datasets.

## Technologies


* **Data Source:** sailing telemetry and boat metadata

  * **Telemetry Metrics (per session/boat):** speed through water, speed over ground, wind speed, wind direction, heading, GPS position, sail loads, velocity made good, ... , heel angle degrees

    * **Datasets:** [Jengu Nab Tower.csv](https://drive.google.com/file/d/1DLbsLb_M2QJ8YCfTlCDxEbq-IlV4ITjF/view?usp=sharing), [Technative 1.csv](https://drive.google.com/file/d/1_X8xfJUCntw_Z6HmD6Qzz8I1HPPoC8J8/view?usp=sharing), [SHADOW.csv](https://drive.google.com/file/d/1axMG3S7p5keu7JwlGigP4DS4hsUdca5T/view?usp=sharing)
  * **Boat Metadata:** session ID, boat name, ... , session notes

    * **Dataset:** [Boat info.csv](https://drive.google.com/file/d/1R0hmQEOb4ZoPlqk6lu3k_k-nEGC2iC8M/view?usp=sharing)


* **Language:** Python
* **Visualisation:** Matplotlib, NumPy, Pandas

## Data Architecture

* Data is extracted from structured datasets provided by the client (Ashtree Marine)
* Data is cleaned, merged, and time-aligned for multi-session analysis
* Comparative visualisations (e.g. multi-line charts, overlaid track maps, heatmaps, correlation graphs, box plots) are created using Python
* Analytical outputs are designed to improve clarity and support performance insights
