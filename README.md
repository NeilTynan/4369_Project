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


The time frame for review has been set to 2001-2022. This is to account for the fact that the SFI data starts in 2001 while there is the OECD data terminates in 2022.

## Use of this Project

This repository may be of some interest to other students engaged in similar projects around programming for data analytics. Feel free to use whatever you like from it (though if another party has been referenced, I would ask that you likewise cite them).

## Getting Started

The workbook is structured in a linear fashion, so reading through it from start to finish is the best approach.

To understand how the workbook has developped to date, please see below a timeline of the work done on the notebook and the material referenced in the course of this work:
- 21/11/2024 - Created ReadMe and Gitignore file, mirroring the structure of 4369_assignments. Gitignore file generated using the template at Python gitignore template at https://github.com/github/gitignore/blob/main/Python.gitignore, the Windows gitignore template at https://github.com/github/gitignore/blob/main/Global/Windows.gitignore, the MacOS gitignore template at https://github.com/github/gitignore/blob/main/Global/macOS.gitignore and the Linux gitignore template at https://github.com/github/gitignore/blob/main/Global/Linux.gitignore. Created "project.ipynb" notebook and started work on project by loading in SFI files on ORCiD adoption amoung grant holders and begining to chart the data.
- 23/12/2024 - Added in Date ranges to SFI data analysis, as per course material "TPFDA6.2 manipulating timeseries". Added legend to SFI line chart. External material referenced include: https://stackoverflow.com/questions/11983024/matplotlib-legends-not-working (adding a legend to STR charts), https://matplotlib.org/stable/api/markers_api.html (Matplotlib marker functions). Started work on loading in the OECD API.
- 30/12/2024 - OECD data loaded in. Started work on processing the OECD data and generating charts on the data related to Irish researchers.
- 03/01/2025 - Completed work on OECD data/charts. Started to work on merging the two datasets for analysis.
- 04/01/2025 - Finished merging data sources. All charts completed.

## Getting help

Queries about this repository can be directed directly to my GitHub account (NeilTynan).

## Other References

[Python for Data Analytics, 3E](https://wesmckinney.com/book/) - Chapter 9 was regularily refereced in the production of the charts used in this project.
https://info.orcid.org/what-is-orcid/services/public-api/
https://aeturrell.github.io/coding-for-economists/data-extraction.html
https://www.delftstack.com/howto/matplotlib/add-trendline-in-python-matplotlib/ bar chart
https://stackoverflow.com/questions/46658232/pandas-convert-column-with-year-integer-to-datetime datetime issue format y
https://www.geeksforgeeks.org/how-to-add-one-row-in-an-existing-pandas-dataframe/ add a new row

## Author

I am student Atlantic Technological University's Higher Diploma in Data Science.