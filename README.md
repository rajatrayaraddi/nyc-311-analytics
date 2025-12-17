# Spatiotemporal Analytics and Data-Driven Pattern Mining in Urban Complaints
This project analyzes New York City’s 311 service request data using spatial-temporal analytics, data mining, and machine learning to uncover patterns in complaint behavior across time, location, and service categories. The study performs exploratory analysis, geospatial clustering, contrast and sequential pattern mining, anomaly detection, time-series forecasting, and resolution-time prediction.

## Important Notes
- A fully interactive version of `main.ipynb` is available at: [Google Colab](https://colab.research.google.com/drive/1-8MAb94Gn7sJKuG9dWDu4IRkZTjIGzLp?authuser=1#scrollTo=bfa93f9e)
- The notebooks are best viewed and executed locally with all required dependencies installed; otherwise, interactive visualizations generated using Prophet, Plotly, and Folium may not render correctly.
- The `misc.ipynb` notebook is not intended to be run sequentially, as it contains isolated cells from exploratory and experimental analyses.

## Repository Structure
- `main.ipynb`: Main notebook containing exploratory data analysis, data mining tasks, model training, results, and visualizations.
- `vis_anomaly.ipynb`: Notebook with focused and readable visualizations for anomaly detection of complaint volume spikes.
- `data_cleaning.ipynb`: Data preprocessing and cleaning pipeline, including feature engineering and encoding steps.
- `data_reduction.ipynb`: Code used to reduce the original dataset to the 10 million row subset used in this analysis.
- `misc.ipynb`: Secondary analyses, exploratory experiments, and discarded or failed modeling attempts.

## Getting Started
- ```bash
  pip install -r requirements.txt
  ```
- The `main.ipynb` notebook requires the cleaned dataset to run. Cleaned subsets of 1 million and 10 million records are available at: [Google Drive](https://drive.google.com/drive/folders/12OJPEONHrgj9wPlaK0LTAHlq4rEApsGQ?usp=share_link)

## Dataset
The full NYC 311 Service Requests dataset is available at: [NYC 311 Service Requests (NYC Open Data)](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data)

## Draft Paper
A detailed write-up of this work is available on [Zenodo](https://doi.org/10.5281/zenodo.17956488).

## License
This project is released under the [MIT License](LICENSE).
