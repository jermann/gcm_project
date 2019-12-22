# Building Factors using Natural Language Processing on Regulatory Filings
Project for Global Capital Markets, under supervision of Prof. Dastidar, Columbia University, December 2019

## Summary
This project examines textual similarities between regulatory filings of U.S. public companies as a signal of an assets future performance. Cohen et al. (2018) provided empirical evidence of positive abnormal returns in the time period of 1994-2014. We explore the textual similarities predictive power for abnormal returns in subsequent years, specifically between 2015-2018 and find that the returns can be replicated for the years 2015-2016 but subside since then. The github repository contains all necessary information to replicate my results.

## About this repository
This repository contains the main paper where I present my findings. The version with the appendix also contains all the code that was used to generate the results. In order to replicate the results, I have included the two `.ipynb` files which are python notebooks comprised of individual code cells similarly to a Python shell. I have included a short description on how to run the files below. 

## Running the notebooks
0. Install jupyter notebooks and python if you haven't done so. The following [link](https://jupyter.org/install) contains the installation information
1. Open the terminal app
2. Run `jupyter notebook`
3. From the browser that was automatically opened, navigate to the location of the `.ipynb` files
4. Open notebooks

## Getting the data
The data can be retrieved from to locations. The first contains all the intermediary metrics that were computed. And the second one contains all the original data. 
1. [Metrics Data](http://alexanderjermann.com/gcm_project/data.zip)
2. [10-K and 10-Q reports](https://sraf.nd.edu/data/stage-one-10-x-parse-data/)
