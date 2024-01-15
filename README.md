# Bitcoin Projects

### Overview

This repository contains a collection of data projects related to the bitcoin price series. The Time Series Analysis project focuses on exploring the time series properties of the bitcoin price series and modeling the seasonality and trend components. Then the Factor Analysis project explores the relationship between the bitcoin price series within the context of some traditional asset pricing models, such as the Fama-French 3-Factor Model and the Fama-French 5-factor model. Each of the R Notebooks contains a more detailed overview before the data work begins.

### Repository Structure

The data work for these project demos is contained in the R Notebook directories of this repository. On GitHub, the webpages should display the README.md files, which contain the compiled output of the R Notebooks. If you wish to explore the source codes locally, then you can open the .Rmd files in RStudio and execute the code chunks to replicate the data work. Note the `output: html_notebook` line in the header of that file, which indicates that the R Markdown document is an R Notebook. 

After exploring the R Notebook and making any desired changes, you can then create a copy that will appear on GitHub. To do this, save a copy of the R Notebook and name it README.Rmd. Then, change the header line to `output: github_document`, which will switch the file from being an R Notebook to an R Markdown file that will compile into a generic [Markdown](https://www.markdownguide.org/) file (.md). This format (along with the README name) will automatically be recognized by GitHub and displayed in-browser. This will also replace the Preview button with an option to Knit the Markdown file. This knitting process will re-run all the code chunks and generate a new README.md file inside of the R Notebook folder, which will display on GitHub.

