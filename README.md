# Calcium-Analysis
Matlab 2019b
Processed multiple files and multiple ROIs within one file

Works for a particular image processing pipeline (ImageJ/FIJI), where the first ROI is background. Data files should also contain information on aspect ratio and area of ROIs
Current code takes csv files from a folder, displays individual traces and data. The user decided which ROIs are of interest and annotates results. The data is analyzed using MATLAB functions. Saves a summary file and data/traces of individual ROIs.
All displayed peaks/data are included in the individual ROI files but outliers (eg. fall time for a double peak) are excluded from averages in the summary file.
