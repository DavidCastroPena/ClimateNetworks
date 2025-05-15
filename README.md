# Simulating Belief Diffusion for Strategic Campaign Timing

This repository contains the code, data, and documentation for the agent-based simulation described in the paper:

**"Simulating Belief Diffusion for Strategic Campaign Timing: An Agent-Based Approach Using a Twitter Sustainability Network"**  
*David F. Castro Pena, Management Science Department, Stanford University*

## Overview
This project models belief diffusion over a Twitter-derived social network using agent-based simulation. Each agent represents a Twitter user with evolving beliefs (supportive, resistant, or neutral) about ecosystem services. Agents follow behavioral rules inspired by political psychology and distributive politics to update their beliefs based on their neighbors.

### Requirements

- R (>= 4.2.0)
- R packages: `igraph`, `R6`, `data.table`, `ggplot2`, `dplyr`, `tidyr`, `quarto`

###Data Source
The data for the elaboration of this analysis was extracted from:
Bruzzese, S., Ahmed, W., Blanc, S., & Brun, F. (2022). Ecosystem services: A social and semantic network analysis of public opinion on Twitter. International Journal of Environmental Research and Public Health, 19(22), 15012. https://doi.org/10.3390/ijerph192215012
