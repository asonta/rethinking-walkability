# rethinking-walkability
Code for "Rethinking Walkability" paper

## Where to access data
Before running any of the code in the Python or R files, first download the relevant datasets from the following sites and place them in a "data" folder in the project directory. When running the Python notebook, please make sure the downloaded file names match the file names used in the Python code.
- [EPA Smart Location Database](https://www.epa.gov/smartgrowth/smart-location-mapping)
- [Baltimore Ecosystem Study Houshold Telephone Survey](https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-bes.4000.180)

## Running code
1. `survey_analysis.ipynb` includes code for preprocessing and stitching together the two datasets.
2. `pls_sem_final.Rmd` includes code for running the Partial Least Squares Structural Equation Modeling analysis in R.

Note: the `pls_sem_final.html` file includes the same code as the `.Rmd` file but with rendered outputs and plots.
