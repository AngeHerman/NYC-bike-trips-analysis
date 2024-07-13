# New York City Bike Trips Analysis

## Description
This project analyzes bike trip data in New York City from 2014 to 2023. The goal is to provide detailed insights and visualizations on trip trends, peak hours, the most popular stations, and the most frequent trips using various visualization tools, including GeoPandas for maps.

## Table of Contents
- Data
- Data Preprocessing
- Visualizations
- Installation and Execution
- Results
- Conclusion
- License

## Data
The data used in this project comes from the public archives of New York City bike trips from 2014 to 2023 (~80 GB of data).

- [NYC Bike Data](https://s3.amazonaws.com/tripdata/index.html)

## Data Preprocessing
The data cleaning and preparation steps include:
1. Loading and merging datasets.
2. Handling missing values.
3. Converting date and time formats.
4. Creating new columns for analysis (e.g., time of day, day of the week, etc.).

## Visualizations
The visualizations created for this project include:
1. Number of trips per hour.
2. Distribution of trips by day of the week.
3. Map of the most frequent trips.
4. Most popular stations for departures and arrivals.
5. Peak hour analysis for trips.
6. Geographical maps of trips by day of the week and by hour using GeoPandas.

## Installation and Execution
To run this project locally, follow the steps below:

1. Clone this repository:
    ```sh
    git clone https://github.com/your_username/nyc-bike-trips-analysis.git
    ```

2. Navigate to the project directory:
    ```sh
    cd nyc-bike-trips-analysis
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Launch the Jupyter notebook:
    ```sh
    jupyter notebook
    ```

5. Open and run `project.ipynb`.

## Results
The visualizations show the following trends:
- Hours with the highest number of trips.
- Days of the week most conducive to bike trips.
- Most used stations for departures and arrivals.
- The most frequent trips in the city.
- Geographical maps detailing trips by day and by hour.

## Conclusion
This analysis provides an overview of bike trips in New York City. The insights gained can help identify peak hours, the most popular stations, and the most common trips, thereby aiding in the improvement of bike-sharing infrastructure and services.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors
- **Ange Herman**
- **Jasen Steeve**
