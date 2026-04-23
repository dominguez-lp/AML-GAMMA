CSCI 5420 – Applied Machine Learning I
File: README.txt

PROJECT TITLE: Group Project - Final Phase
AUTHORS: Emily Clauss and Laura Dominguez
LAST UPDATED: 4/13/2026

DESCRIPTION: 
This project was completed as part of the CSCI 5420 - Applied Machine Learning course at New Mexico State University during Spring 2026.
The objective of this analysis is to examine socioeconomic factors that influence crime rates across the United States. 
Using machine learning techniques, we identify and evaluate predictive features associated with variations in crime.
This project demonstrates data preprocessing, exploratory data analysis, feature selection, and predictive modeling to generate insights from
2024 Census Data https://data.census.gov/ and 2024 FBI Crime Data https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/home.

FOLDERS INCLUDED:
DATA: Stores raw and processed datasets
-PROCESSED_CENSUS_DATA
-PROCESSED_CRIME_DATA
-RAW_CENSUS_DATA
-RAW_CRIME_DATA

FIGURES: Contains all generated visualizations
-Figure_1 through Figure_15

NOTEBOOKS
-NOTEBOOKS\01_CRIME_DATA_COLLECTION.ipynb01_CRIME_DATA_COLLECTION.ipynb: A Jupyter Notebook that performs data loading, cleaning, processing, and plotting.
-NOTEBOOKS\02_CRIME_DATA_EDA.ipynb: A Jupyter Notebook that runs an initial call for data from the FBI API
-NOTEBOOKS\03_CENSUS_DATA_PREPROCESSING_EDA.ipynb: A Jupyter Notebook that performs data loading, cleaning, processing, and plotting for all 50 US states.
-NOTEBOOKS\03_CENSUS_DATA_PREPROCESSING_EDA_UPDATED.ipynb: A Jupyter Notebook that performs data loading, cleaning, processing, and plotting for US counties.
-NOTEBOOKS\04_PREDICTIVE_MODELS.ipynb: A Jupyter Notebook that performs data classification using available SCIKIT-Learn Classific ation Models for all 50 US States. 
-NOTEBOOKS\04_PREDICTIVE_MODELS_UPDATED_COUNTY.ipynb: A Jupyter Notebook that performs data classification using available SCIKIT-Learn Classific ation Models for US counties.

SYSTEM REQUIREMENTS:
- Python 3.x
- Anaconda
- Jupyter Notebook
- pip (Python package installer)

HOW TO SETUP AND RUN:
1. Ensure Python 3.13.0 (version 3.x or higher) is installed on your system.
2. Install required Python libraries: Open a terminal or command prompt and run the following command:
    pip install pandas numpy matplotlib seaborn
3. Running the Script: Navigate to the directory containing "GAMMA_Phase3.ipynb" and "Phase3_CENSUS.ipynb" and "GAMMA_Counties_Data_NM_CO.ipynb" using a terminal or command prompt and execute the following command:
    jupyter notebook
4. You will be directed to a new web browser window. Click on the files in this order for analyis on the 50 states: 
    a. 01_CRIME_DATA_COLLECTION.ipynb
    b. 02_CRIME_DATA_EDA.ipynb
    c. 03_CENSUS_DATA_PREPROCESSING_EDA.ipynb
    d. 04_PREDICTIVE_MODELS.ipynb
Click on the files in this order for analyis on available US counties:
    a. 01_CRIME_DATA_COLLECTION.ipynb
    b. 02_CRIME_DATA_EDA.ipynb
    c. 03_CENSUS_DATA_PREPROCESSING_EDA_UPDATED.ipynb
    d. 04_PREDICTIVE_MODELS_UPDATED_COUNTY.ipynb
6. On the tool bar, per each juptyer file click Run > Run All Cells
NOTE: Ensure all data files listed above are in the same directory as the script or update the script with the correct
file path. Files regarding the counties are a work in progress and expected to change until the end of Spring 2026 Semester 5/12/2026.

EXPECTED OUTPUT:
The notebooks will clean datasets and provide visualizations of each respective dataset. 

TROUBLESHOOTING:
- If the script fails to execute, check that all required packages are installed correctly and Python is updated
to the latest version. Also check that you executed the notebooks in the respective order.
- Verify the path to all datasets is correct if the script cannot find the file.
- Ensure all data files are in the same directory as the script or update the script with the correct file path.
- Ensure that the FBI API is active and working by checking if request is accepted by FBI server.


CONTACT: For any further assistance, please contact efclauss@nmsu.edu or laudom5@nmsu.edu 



