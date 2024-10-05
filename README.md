
## Electric Vehicle Data Analysis Project

# Project Overview

This project focuses on analyzing Electric Vehicle (EV) data using Python. The dataset includes various details such as vehicle make, model year, electric range, and location data. The analysis involves:

Performing exploratory data analysis (EDA) to understand the data trends.

Visualizing the data using a Choropleth map to display the distribution of EVs based on location.

Creating an animated Racing Bar Plot to visualize the count of EVs by make over the years.

Sharing insights and learnings in a LinkedIn post.


# Dataset

The dataset used in this project contains the following columns:

VIN (1-10): First 10 digits of the Vehicle Identification Number.

County: County where the vehicle is registered.

City: City where the vehicle is located.

State: State where the vehicle is located.

Postal Code: Postal code of the vehicle location.

Model Year: Year of manufacture of the electric vehicle.

Make: Vehicle manufacturer (e.g., Tesla, Nissan).

Model: Specific model of the vehicle.

Electric Vehicle Type: Type of electric vehicle (e.g., Battery Electric Vehicle).

CAFV Eligibility: Clean Alternative Fuel Vehicle eligibility status.

Electric Range: Electric range in miles.

Base MSRP: Manufacturer’s suggested retail price.

Legislative District: Legislative district of the vehicle location.

DOL Vehicle ID: Department of Licensing vehicle ID.

Vehicle Location: Additional location details for the vehicle.

Electric Utility: Name of the electric utility servicing the vehicle.

2020 Census Tract: Census tract based on the vehicle location.


# Project Structure

Task 1: Exploratory Data Analysis (EDA)

Univariate and bivariate analysis of the dataset.

Distribution plots and scatter plots for important variables like Electric Range, Base MSRP, Make, etc.


Task 2: Choropleth Map

A Choropleth map was created using Plotly to visualize the distribution of EVs based on location (State level).


Task 3: Racing Bar Plot Animation

A Racing Bar Plot was created to display the animation of electric vehicle make counts over the years.


# Technologies Used

Python: The core programming language used for data analysis and visualization.

Pandas: For data manipulation and analysis.

Seaborn/Matplotlib: For static visualizations in exploratory data analysis.

Plotly: For creating interactive visualizations (Choropleth and Racing Bar Plot).

Jupyter Notebook: For writing and executing the project code.


# How to Run the Project

1. Clone the repository or download the project files.


2. Install the necessary dependencies using the following command:

pip install -r requirements.txt


3. Open the Jupyter Notebook file electric_vehicle_analysis.ipynb.


4. Run the notebook cells to see the analysis, visualizations, and animations.



# Requirements

Python 3.x

Pandas

Numpy

Matplotlib

Seaborn

Plotly


You can install the required libraries using:

pip install pandas numpy matplotlib seaborn plotly

Visualizations

Choropleth Map

A Plotly Choropleth map displaying the number of electric vehicles based on state location.

Racing Bar Plot

A Plotly animated racing bar plot that shows the number of electric vehicles by make over the years.

# Author
# Suresh Kumar D.
B.E. Computer Science and Engineering (CSE)
Final Year Student at Gojan School of Business and Technology


# Acknowledgments

Thanks to Innomatics Research Labs for providing guidance and resources for this project.
