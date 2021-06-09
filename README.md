# laptime-predictor
Takes regular laptimes plus correlated track and air temps as well as other parameters and plots graphs showing the optimal values for those parameters.

## Problem:
Often times, equipment manufacturers do not show the exact optimum value for pressure or temperature of their products. This can be for many reasons; variance of manufacturing, secrecy benefiting factory teams, or simple lack of knowledge. To ensure that you are running at the optimum values (or within an acceptable deviation of those values), you must first find those values through trial and error. This procedure can take a long time and involve difficult manual calculations or simple guesses.

## Overview:
This program's goal is to take laptimes with correlated track temperature, tyre pressures, and other miscellaneous sources of data and output graphs showing the correlation between those values and laptimes in order to assist with finding optimal values or settings for the equipment.

## Inputs: 
- List of laptimes with correlated track temp, tyre pressures, and other settings

## Outputs:  
- Chart showing correlation between a selected parameter's value and laptime

## Procedure:
- [ ] Load data from .json exported from ARC or load data from manually constructed spreadsheet
- [ ] Filter out unimportant data from ARC such as names, info, stuff like that
- [ ] If using ARC, add in 
- [ ] Create graph from laptimes and a selected other value
