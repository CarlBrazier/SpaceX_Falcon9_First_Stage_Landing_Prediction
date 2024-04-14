# IBM Professional Data Scientist Certification
This was the capstone project for my [IBM Professional Data Scientist Certification](https://www.coursera.org/professional-certificates/ibm-data-science) 

![image](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/assets/165842156/a102a503-e67a-42ba-806f-13890e9fbfab)
## SpaceX Falcon 9 First Stage Landing Prediction

In this project, I predicted if the Falcon 9 first stage would land successfully. SpaceX advertised Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings was because SpaceX could reuse the first stage. Therefore if it was determined if the first stage would land, the cost of a launch could be determined. This information could be used if an alternate company wanted to bid against SpaceX for a rocket launch.

### [SpaceX API Data Collection](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/blob/main/jupyter-labs-spacex-data-collection-api.ipynb)
- Data Collection: Retrieved data via the SpaceX API, including launch details like dates, rocket type, and payload mass.
- Data Cleaning: Addressed missing values and transformed data for analysis.
- Data Analysis: Conducted exploratory analysis to identify trends in launch data.
- Data Exporting: Saved the cleaned data to a CSV file for further use.

### [Data Wrangling](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/blob/main/labs-jupyter-spacex-Data-wrangling.ipynb)
- Exploring Launch Sites: Analyzed the number of launches from different SpaceX launch sites.
- Examining Orbit Types: Understood various orbit types targeted by these launches.
- Data Cleaning: Prepared the data by handling missing values and removing unneeded columns.
- Data Export: Saved the cleaned and processed data into a CSV file for further analysis.

### [Web Scraping Launch Records from Wikipedia](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/blob/main/jupyter-labs-webscraping.ipynb) 
- Data Retrieval: Retrieved data from a static URL pointing to a specific revision of a Wikipedia page on Falcon 9 and Falcon Heavy launches.
- Data Parsing: Initial steps used requests.get() to fetch the webpage content for scraping.

### [EDA - SQL](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/blob/main/jupyter-labs-eda-sql-coursera_sqllite.ipynb)
- Database Connection: Established a connection to a local SQLite database to store and retrieve the SpaceX dataset.
- Data Loading: Involved reading the downloaded CSV file containing the SpaceX launch data and loading this data into a SQL table within the SQLite database. This step was critical for performing SQL-based data manipulation.
- Data Analysis SQL Queries: Performed operations such as filtering, sorting, and aggregating data to extract insights related to the economics of SpaceX launches, focusing on the reusability of the Falcon 9 rocket's first stage, to determine the cost implications of landing the first stage of the Falcon 9.

### [EDA Through Data Visualisation](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/blob/main/jupyter-labs-eda-dataviz.ipynb) 
- Data Loading: Utilized the Pandas library to load the CSV data directly into a DataFrame for immediate manipulation and analysis.
- Data Visualization: Employed Matplotlib and Seaborn for creating visualizations.
  - Categorical scatter plots to analyze the relationship between flight number and payload mass, categorized by mission outcome (success or failure).
  - Scatter plots to assess the correlation between launch sites, payload mass, and other relevant mission details, providing insights into factors influencing launch success.

### [Data Visualisation: Dashboard](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/blob/main/jupyter-labs-build-a-dashboard-application-v10.ipynb)
- Library Installations: Installed Plotly, Pandas, and Dash.
- Dashboard Components: Set up a Plotly Dash application that included various interactive components such as dropdown lists and range sliders.
- Visualization Features:
  - Pie charts to analyze launch success rates based on selected criteria from dropdown menus.
  - Scatter plots to explore correlations between payload mass and other launch variables.
  - These visualizations were interactive, allowing users to select different parameters and instantly see updated results.

### [Locations Analysis with Folium](https://github.com/CarlBrazier/SpaceX_Falcon9_First_Stage_Landing_Prediction/blob/main/lab_jupyter_launch_site_location.ipynb)
- Libraries: Used folium for geographic data visualization and wget for downloading data from the internet.
- Data Handling: The data was loaded into a Pandas DataFrame, where preprocessing steps involved selecting relevant columns like launch site names and coordinates, and aggregating data by launch site.
- Data Visualization: Employed the folium library to create interactive maps that visually represented the locations of the SpaceX launch sites.
  - Interactive Features:
    - Utilized plugins like MarkerCluster and MousePosition to enhance the interactivity of the maps, providing more context and usability for users exploring the map.
    - Markers were added to the maps to pinpoint the exact locations of the launch sites, with additional functionalities like zoom and scroll for detailed examination.
- Exploratory Data Analysis (EDA):
  - Geographical Analysis: Focused on analyzing the strategic positioning of launch sites in relation to their geographical settings.
  - Visual Insights: Offered insights into how the location of a launch site might influence launch success rates and logistical considerations, using the visual medium of maps for better understanding.


