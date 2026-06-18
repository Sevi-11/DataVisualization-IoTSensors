# IoT Sensor Data Visualization

This repository contains a Jupyter Notebook that analyzes and visualizes IoT sensor data from the `iot_sensor_data.csv` dataset. The notebook uses various data visualization techniques to explore patterns and relationships within the data.

## Dataset

The `iot_sensor_data.csv` dataset contains sensor readings from various IoT devices, including information about location, humidity, light intensity, temperature, and battery levels.

## Libraries Used

The following Python libraries are used in the notebook:

*   **pandas:** For data manipulation and analysis.
*   **matplotlib:** For creating static, animated, and interactive visualizations.
*   **plotly:** For creating interactive graphs and charts.

## Visualizations

The notebook generates the following visualizations:

1.  **Device Location Distribution:** A bar chart showing the distribution of IoT devices across different locations.
2.  **Average Hourly Humidity per Day:** A series of line plots showing the average humidity for each hour of the day, with a separate plot for each date.
3.  **Average Hourly Light Intensity per Day:** A series of line plots displaying the average light intensity for each hour, faceted by date.
4.  **Average Hourly Temperature vs. Battery per Day:** A grouped bar chart comparing the average temperature and battery level for each hour, with subplots for each day.
5.  **Device Type Distribution:** A horizontal bar chart illustrating the distribution of different types of IoT devices.

## How to Run

1.  Ensure you have Python and Jupyter Notebook installed.
2.  Install the required libraries:
    ```bash
    pip install pandas matplotlib plotly
    ```
3.  Place the `iot_sensor_data.csv` file in the same directory as the notebook.
4.  Open and run the `Data Visualization.ipynb` notebook in Jupyter.
