### Julia file

"DVC_Clean_Julia_experiment_01.ipynb": 

Experiment related to multistage game. Copied to "Game_Julia01.ipynb".

This file implements a duopoly market model with heterogeneous consumers. The model simulates 100 consumers with different preferences (towards product functionality and data restrictions) and uses value iteration to compute Nash equilibria under various data restriction scenarios. 

For each data restriction level, the model computes each firm's best-response pricing strategy given their competitor's price, generating best-response curves. The Nash equilibria are found at the intersections of these best-response curves.

Julia version: 1.11.5

Packages:

using Distributions, Random, MvNormalCDF
using Query, Plots, StatsPlots
using DataFrames, CSV, Dates
