# README

## Description
This jupyter notebook plots time series data for the year 2012 from the main Balmorel input exel file (Data.xlsm), including:
- solar power production (spp)
- variable electricity demand (ved)
- variable heat demand (vhd)
- variable wind generation (vwg)

Available countries:
- Germany (DE)

Each commodity is plotted for all countries and vice versa.
The respective output directories are created automatically.

## Usage
The user can decide for which countries to run the script and which seasons (weeks) and termns (hours) to plot and highlight.

By default:
- all 52 seasons per year,
- all 168 terms per season are plotted and 
- every 24th term is highlighted to indicate the length of one day.

## Installation
- In order to avoid trouble shooting, install the requirements.yml file with anaconda.
- To open, edit and execute the script
	1. open the anaconda promt from the windows start menu: type `anaconda prompt`
	2. activate the plotting environment: type `conda activate plotting`
	3. navigate to the project folder: type `cd <path_to_project>`
	4. and then start the notebook editor: type `jupyter notebook`
