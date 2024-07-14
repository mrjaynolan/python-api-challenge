# WeatherPy Analysis

Loading the WeatherPy Notebook

<img width="711" alt="Screenshot 2024-07-13 at 11 04 11 PM" src="https://github.com/user-attachments/assets/520b48fb-22ee-4153-ac95-1597abafb3a2">

#### Analyzing WeatherPy Notebook

Based on the provided notebook, here's a summary of what WeatherPy does:

1. Setup and Dependencies: The notebook starts by importing necessary libraries such as Pandas, Matplotlib, and Requests. It also loads the OpenWeatherMap API key from a separate file.

2. Data Retrieval: It generates a list of random cities and retrieves weather data for these cities using the OpenWeatherMap API. The data includes temperature, humidity, cloudiness, and wind speed.

3. Data Processing: The notebook processes the retrieved data, cleaning it and preparing it for analysis.

4. Visualization: Several scatter plots are created to visualize the relationship between latitude and various weather parameters (temperature, humidity, cloudiness, and wind speed).

5. Output: The notebook saves the results, including the processed data and the generated plots.


### VacationPy Analysis

Loading the VacationPy Notebook

<img width="712" alt="Screenshot 2024-07-13 at 11 04 32 PM" src="https://github.com/user-attachments/assets/298fb70a-6055-4db2-8014-5c5588c15db5">

#### Analyzing VacationPy Notebook

Based on the provided notebook, here's a summary of what VacationPy does:

1. Setup and Dependencies: Similar to WeatherPy, it starts by importing necessary libraries and loading API keys from a separate file.

2. Data Filtering: The notebook filters the cities based on ideal weather conditions, such as temperature and humidity.

3. Hotel Search: It uses the Geoapify API to find hotels near the filtered cities.

4. Visualization: A map is generated to show the ideal vacation spots and nearby hotels, providing a visual representation of the filtered data.

5. Output: The notebook saves the results, including the processed data and the generated map.

# README for WeatherPY

<img width="721" alt="Screenshot 2024-07-13 at 11 04 53 PM" src="https://github.com/user-attachments/assets/5cba6907-68bd-4a02-965f-e557d7f8466a">



2. Install the required Python libraries.

<img width="678" alt="Screenshot 2024-07-13 at 11 05 01 PM" src="https://github.com/user-attachments/assets/c7994310-e7e5-4547-8ed8-a7e3919ffe8c">

3. Obtain an API key OpenWeatherMap and add it to the 'api_keys.py' file.

<img width="679" alt="Screenshot 2024-07-13 at 11 05 08 PM" src="https://github.com/user-attachments/assets/9235da2e-70c6-449b-bea0-7a68bf1ffdb0">



## Usage

1. Run the 'WeatherPy.ipynb' Jupyter Notebook.
2. The notebook will:
       * Generate a list of random cities.
       * Retrieve weather data for these cities using the OpenWeatherMap API.
       * Perfrom data analysis and generate various plots to visualize the weather data.

# Data Analysis

The following analyses are performed in the notebook:

1. Temperature (F) vs. Latitude: Scatter plot to show the relationship between temperature and latitude.
2. Humidity (%) vs Latitude: Scatter plot to show the relationship between humidity and latitude.
3. Cloudiness (%) vs. Latitude: Scatter plot to show the relationship between cloudiness and latitude.
4. Wind Speed (mph) vs. Latitude: Scatter plot to show the relationship between wind speed and latitude.


## Usage

1. Run the VacationPy.ipynb Jupyter Notebook.
2. The notebook will:
      * Filter cities based on ideal weather conditions.
      * Use the Geoapify API to find hotels near these cities.
      * Generate a map visualization showing the ideal vacation spots and nearby hotels.


## Data Analysis

The following analyses are performed in the notebook:

1. Filter Ideal Vacation Spots: Filter cities with ideal weather conditions such as temperature range and humidity.
2. Find Nearby Hotels: Use the Geoapify API to find hotels near the filtered vacation spots.
3. Map Visualization: Generate a map showing the vacation spots and nearby hotels.



