# Companion Materials: Outlier Detection in PM2.5 Air Sensor Networks

Companion materials for **"Detecting outliers in PM2.5 air sensor networks during smoke events using information theory and machine learning"** (Illson & Barkjohn, submitted to *Atmospheric Measurement Techniques*).

The core methods are implemented in the [`elwood-spatial`](https://doi.org/10.5281/zenodo.18856271) package. This repository provides supporting materials to reproduce and extend the analysis.

## Contents

- `notebooks/` — reproducible example notebook
- `models/` — pre-trained XGBoost models
- `data/` — sample data subset from one smoke event
- `site_event_characterization.pdf` — detailed site and event characterization (terrain, land cover, sensor network composition and connectivity, and smoke source attribution per event)

## Data availability

The underlying air quality data were obtained from sources with varying use policies and cannot be redistributed in full. Public-source data (e.g., AirNow) can be re-downloaded directly. The sample subset here is provided to demonstrate the workflow.

## Citation

Illson, S.: Companion Materials: Outlier Detection in PM2.5 Air Sensor Networks, Zenodo, https://doi.org/10.5281/zenodo.18897333.

## License

Released under CC-BY-4.0.