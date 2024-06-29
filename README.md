
# Data Preparation and Plotting Visualizations on FARS Data using Python

In this Project, the data about the Fatalities of US Road accidents were analyzed and the patterns were studied by plotting visualizations using Python packages.  The Data was taken from various sources such as flat files, APIs, and web data. 


## Project Overview

- Data from 3 type of sources such as Flat files, Website and API data were read using Python and Data transformations and cleansing was done before merging them together. 
- The combined data was loaded into SQLite database 
- The Patterns in the data was analyzed by plotting visualizations on the combined data using Python libraries such as Plotly, Seaborn and Matplotlib.

## Prerequisites

1.  Python version 3.8 or above is required to run the code available in the .pynb format.
Jupyter Notebook or similar interface is preferred. 

2.  Various Python libraries are required for the project execution. They can be installed using the command:

    pip install <library name>

    On Jupyter use the command  !pip install <library name>

3. The flatfiles required for the project are available in the link:

    https://static.nhtsa.gov/nhtsa/downloads/FARS/2021/National/FARS2021NationalCSV.zip

From the zip file, the below files should be extracted and placed in the same location where the source code resides:

- person.csv
- race.csv
- weather.csv



## Deployment

To deploy this project execute the scripts in the below order

    1. Sourcing_FlatFilesData.pynb

    2. Sourcing_WebData.pynb

    3. Sourcing_API_Data.pynb

    4. Merging_and_Building_Visualizations.pynb
