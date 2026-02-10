# ThinkStats

## Chapter one Data 

| Column Name | Description                                                                                       |
|-------------|---------------------------------------------------------------------------------------------------|
| caseid      | Integer ID of the respondent.                                                                     |
| pregordr    | Pregnancy serial number (1 = first pregnancy, 2 = second, etc.).                                  |
| prglngth    | Duration of the pregnancy in weeks.                                                               |
| outcome     | Outcome code of the pregnancy (1 = live birth).                                                   |
| birthord    | Serial number for live births (1 = first child, 2 = second, etc.). Blank for non-live births.     |
| birthwgt_lb | Pounds part of the baby’s birth weight.                                                           |
| birthwgt_oz | Ounces part of the baby’s birth weight.                                                           |
| agepreg     | Mother's age at the end of the pregnancy.                                                         |
| finalwgt    | Statistical weight representing how many people in the U.S. population the respondent represents. |

## My Work

My personal work and exercises can be found in the [my-work](my-work/) folder.

This repository contains notebooks, data, and supplementary material for the third edition of *Think Stats*.

[Click here to read the book online and run the notebooks](https://allendowney.github.io/ThinkStats/).

## Downloadable Files

- **[ThinkStats.zip](https://github.com/AllenDowney/ThinkStats/raw/refs/heads/v3/ThinkStats.zip)**: Zip file of notebooks without solutions (download this if you just want to run the notebooks without cloning the repository)  
- **[ThinkStatsSolutions.zip](https://github.com/AllenDowney/ThinkStats/raw/refs/heads/v3/ThinkStatsSolutions.zip)**: Zip file of notebooks with solutions  


## Directories

- **data**: Data files used in the book  
- **examples**: Notebooks with additional examples  
- **figs**: Figures other than the ones generated in the notebooks  
- **jb**: Directory where I build the HTML version of the book with Jupyter Book  
- **nb**: Notebooks without solutions  
- **soln**: Notebooks with solutions (these are the source files)  
- **tutorial**: Notebooks for a tutorial on time series analysis  


## Setup

- **Makefile**: Instructions for creating a Conda environment for the book  
- **requirements.txt**: Required packages to run the notebooks  
- **requirements-dev.txt**: Additional packages used for developing the notebooks
