# Programming for Data Analytics - Project

This README has been written with [GitHub's documentation on README's](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) in mind.

## About this Project

This repository contains my project for ATU module 4369 -- PROGRAMMING FOR DATA ANALYTICS. As part of this project, we are expected to come up with a question to examine. Then we are expected to:
- Read in a number of datasets related to the subject matter
- Analyze the data using various techniques 
- Illustrate your findings

The other repositiories for this course can be found at:
- Assignment folder: https://github.com/NeilTynan/PFDA-assignments
- Course Work folder: https://github.com/NeilTynan/PFDA-mywork

For my project quesion, I have sought to estimate the number of researchers in Ireland who would be presenting ORCiDs if they obliged to follow SFI's ORCiD policies. The time frame for review has been set to 2001-2023. This is to account for the fact that the SFI data the Organisation for Economic Co-operation and Development (OECD)'s [Main Science and Technology Indicators (MSTI) database and Science Foundation Ireland (SFI)'s Grant Commitment List.

## Use of this Project

This repository may be of some interest to other students engaged in similar projects around programming for data analytics. Feel free to use whatever you like from it (though if another party has been referenced, I would ask that you likewise cite them).

## Getting Started

The workbook is structured in a linear fashion, so reading through it from start to finish is the best approach.

To understand how the workbook has developped to date, please see below a timeline of the work done on the notebook and the material referenced in the course of this work:
- 21/11/2024 - Created ReadMe and Gitignore file, mirroring the structure of 4369_assignments. Gitignore file generated using the template at Python gitignore template at https://github.com/github/gitignore/blob/main/Python.gitignore, the Windows gitignore template at https://github.com/github/gitignore/blob/main/Global/Windows.gitignore, the MacOS gitignore template at https://github.com/github/gitignore/blob/main/Global/macOS.gitignore and the Linux gitignore template at https://github.com/github/gitignore/blob/main/Global/Linux.gitignore. Created "project.ipynb" notebook and started work on project by loading in SFI files on ORCiD adoption amoung grant holders and begining to chart the data.
- 23/12/2024 - Added in Date ranges to SFI data analysis, as per course material "TPFDA6.2 manipulating timeseries". Added legend to SFI line chart. Started work on loading in the OECD API. External material referenced include: https://stackoverflow.com/questions/11983024/matplotlib-legends-not-working (adding a legend to STR charts), https://matplotlib.org/stable/api/markers_api.html (Matplotlib marker functions), https://stackoverflow.com/questions/46658232/pandas-convert-column-with-year-integer-to-datetime (converting fields to datetime), https://www.statology.org/pandas-group-by-year/ (how to group data by year).
- 30/12/2024 - OECD data loaded in. Started work on processing the OECD data and generating charts on the data related to Irish researchers. External material referenced include: https://aeturrell.github.io/coding-for-economists/data-extraction.html (extracting data from an API), https://www.delftstack.com/howto/matplotlib/add-trendline-in-python-matplotlib/ (adding a trendline to a bar chart).
- 03/01/2025 - Completed work on OECD data/charts. Started to work on merging the two datasets for analysis.
- 04/01/2025 - Finished merging data sources. All charts completed. External materials referenced include: https://www.geeksforgeeks.org/how-to-add-one-row-in-an-existing-pandas-dataframe/(adding a row to an existing dataframe)
- 05/01/2025 - Modeled the data for 2023 from the OECD data. Updated the relevant charts.

## Getting help

Queries about this repository can be directed directly to my GitHub account (NeilTynan).

## Other References

[Python for Data Analytics, 3E](https://wesmckinney.com/book/) - Chapter 9 was regularily refereced in the production of the charts used in this project.
[Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/) - Referenced in the production of the notebook 
[OECD data via API](https://www.oecd.org/en/data/insights/data-explainers/2024/09/api.html) - How to access and use the OECD API
[List of named colors](https://matplotlib.org/stable/gallery/color/named_colors.html) - Names for colours in Matplotlib


## Author

I am student Atlantic Technological University's Higher Diploma in Data Science.