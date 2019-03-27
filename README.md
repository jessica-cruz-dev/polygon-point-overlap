# Polygon/Point Overlap Detection Tool

:star: Files in repository are utilized at The Institute for Health Metrics and Evaluation (An independent global health research center at the University of Washington)

:star: Repository holds most of the work I contributed over the course of my internship (Summer 2018). Most files were compiled to my personal repository after the internship concluded.
 
  
The purpose of the overlap_detect.py tool is to automate the detection of point and polygon overlap for an NID. A codebook is entered and (if applicable) a list of affected NIDs are returned along with infographs and actionable insights for analysts to use to remedy the issue. 

All file paths are currently linked to J drive locations: **J:/temp/jessicac/**, **J:/temp/jessicac/outputs/**, geospatial codebooks and geospatial shapefiles 

## Installing
Step 1. Install Conda:

A powerful package manager and environment manager that you use with command line commands at the Anaconda Prompt for Windows, or in a Terminal window for macOS or Linux.
```
https://docs.anaconda.com/anaconda/install/
```



Step 2. Get Conda Running: 

Follow the sections 'Before you start', 'Contents' and 'Starting conda' on Conda's offical user guide site. 
```
https://conda.io/docs/user-guide/getting-started.html
```


## Create Environment (with environment.yml file)
Use the terminal or Anaconda Prompt for the following.

Step 1. Create the enironment with the environment.yml file provided. The name of your new environment is 'overlap_detect_env'.
```
conda env create -f environment.yml
```
**Please note: Installation of packages and their dependencies will take a while**


Step 2. Activate the environment:
```
Windows:           activate overlap_detect_env
macOS and Linux:   source activate overlap_detect_env
```
Step 3. Verify the new environment was installed correctly 
```
conda list
```
