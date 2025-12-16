# Spatiotemporal Analytics and Data-Driven Pattern Mining in Urban Complaints
This project analyzes New York City’s 311 service request data using spatial-temporal analytics, data mining, and machine learning to uncover patterns in complaint behavior across time, location, and service categories. The study performs exploratory analysis, geospatial clustering, contrast and sequential pattern mining, anomaly detection, time-series forecasting, and resolution-time prediction.

## Repository Structure
- `main.ipynb`: Main notebook containing exploratory data analysis, data mining tasks, model training, results, and visualizations.
- `vis_anomaly.ipynb`: Notebook with focused and readable visualizations for anomaly detection of complaint volume spikes.
- `data_cleaning.ipynb`: Data preprocessing and cleaning pipeline, including feature engineering and encoding steps.
- `data_reduction.ipynb`: Code used to reduce the original dataset to the 10 million row subset used in this analysis.
- `misc.ipynb`: Secondary analyses, exploratory experiments, and discarded or failed modeling attempts.

## Dataset
The full NYC 311 Service Requests dataset is available at: [NYC 311 Service Requests (NYC Open Data)](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data)

## Notes
`prophet` may require additional system dependencies (cmdstan).

## License
This project is released under the [MIT License](LICENSE).
