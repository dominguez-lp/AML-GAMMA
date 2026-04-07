CSCI 5420 – Applied Machine Learning I
File: README.txt

PROJECT TITLE: Group Project - Phase 3
AUTHORS: Emily Clauss and Laura Dominguez
DATE: 03/14/2026

DESCRIPTION: 
The JupyterNotebook 'GAMMA_Phase3.ipynb' opens, compiles, and cleans datasets pulled from FBI crime data. 
The JupyterNotebook 'Phase3_CENSUS.ipynb' opens, compiles, and cleans datasets pulled from Census data. 
These notebooks show our initial analysis of data for our Applied Machine Learning Group Project.

FOLDERS INCLUDED:
DATA: Stores raw and processed datasets
-PROCESSED_CENSUS_DATA
-PROCESSED_CRIME_DATA
-RAW_CENSUS_DATA
-RAW_CRIME_DATA

DOCS: Contains general docs
-TeamTasks.txt

FIGURES: Contains all generated visualizations
-Figure_1 through Figure_15

NOTEBOOKS
-NOTEBOOKS\01_CRIME_DATA_COLLECTION.ipynb01_CRIME_DATA_COLLECTION.ipynb: A Jupyter Notebook that performs data loading, cleaning, processing, and plotting.
-NOTEBOOKS\02_CRIME_DATA_EDA.ipynb: A Jupyter Notebook that runs an initial call for data from the FBI API
-NOTEBOOKS\03_CENSUS_DATA_PREPROCESSING_EDA.ipynb: A Jupyter Notebook that performs data loading, cleaning, processing, and plotting.
-NOTEBOOKS\04_PREDICTIVE_MODELS.ipynb

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
4. You will be directed to a new web browser window. Click on the files in this order: 
    a. 01_CRIME_DATA_COLLECTION.ipynb
    b. 02_CRIME_DATA_EDA.ipynb
    c. 03_CENSUS_DATA_PREPROCESSING_EDA.ipynb
    d. 04_PREDICTIVE_MODELS.ipynb
5. On the tool bar, per each juptyer file click Run > Run All Cells
NOTE: Ensure all data files listed above are in the same directory as the script or update the script with the correct
file path.

EXPECTED OUTPUT:
The notebooks will clean datasets and provide visualizations of each respective dataset. 

TROUBLESHOOTING:
- If the script fails to execute, check that all required packages are installed correctly and Python is updated
to the latest version. Also check that you executed the notebooks in the respective order.
- Verify the path to all datasets is correct if the script cannot find the file.
- Ensure all data files are in the same directory as the script or update the script with the correct file path.
- Ensure that the FBI API is active and working by checking if request is accepted by FBI server.


CONTACT: For any further assistance, please contact efclauss@nmsu.edu or laudom5@nmsu.edu 



