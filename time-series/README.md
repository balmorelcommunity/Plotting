# Plotting of time-series data

The plotting-script plots time-series data from the main Balmorel input exel file (Data.xlsm), including solar power production (spp), variable electricity demand (ved), variable heat demand (vhd) and variable wind generation (vwg) for the year 2016.

- Considered countries are Denmark (DK), Germany (DE), Norway (NO) and Sweden (SE).


The user can decide, which seasons (weeks) and terms (hours) to plot and to highlight. By default all 52 seasons per year and all 168 terms per season are plotted. Besides, every 24th term is highlighted to indicate the length of one day.

Each commodity is plotted for each country and vice versa. The respective output directories are created, if not already existing.


In order to avoid trouble shooting, install the requirements.yml file with all necessary packages and its dependencies.
