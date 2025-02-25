Source: https://github.com/snowflakecorp/snowpark-python-xgboost-realestate 

**********
FROM THE TERMINAL

STEP #1: Create conda environment from yml file
conda env create -f /Volumes/GoogleDrive/My\ Drive/000-demos/17-snowpark-python-xgboost-realestate-main/Streamlit_Realestate_LBC.yml

STEP #2: Activate Conda environment just created
conda activate Streamlit_Realestate_LBC

STEP #3: Update all librairies
conda update --all

STEP #4: Navigate to right folder
cd /Volumes/GoogleDrive/My\ Drive/000-demos/17-snowpark-python-xgboost-realestate-main/

STEP #5: Create "xgboost-model" folder in the directory
--> do it in the jupyter lab

STEP #6: Start Jupyter Lab from terminal with the below command
jupyter lab

STEP #7: Run the SETUP Jupyter Notebook from Jupyter Lab

STEP #8: Run the DEMO Jupyter Notebook from Jupyter Lab

STEP #9: Go the right folder
cd /Volumes/GoogleDrive/My\ Drive/000-demos/17-snowpark-python-xgboost-realestate-main/streamlit

STEP #10: Run the streamlit App
streamlit run Rentabilty_Analysis.py

STEP #6: Reset
conda deactivate
cd ..
conda remove --name Streamlit_Realestate_LBC --all


# Generate configuration files
conda env export > environment_droplet.yml
conda list -e > requirements.txt