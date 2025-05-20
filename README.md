This repository contains all scripts and supporting materials for the third chapter of my PhD dissertation, focusing on spatial multi-species occupancy modeling using data from camera trap surveys.
Overview

The primary goal of this chapter is to analyze carnivore occupancy patterns across multiple sites using a spatial multi-species occupancy model (spMSOM). The analysis is implemented in R using the spOccupancy package.

The repository is structured around two core RMarkdown files:

    01_preprocessing.Rmd
    Prepares and harmonizes raw camera trap data from multiple sites. This includes:

        Data cleaning and formatting

        Spatial data preparation

        Site-level covariate extraction

        Detection history creation

    02_main_model.Rmd
    Implements and runs a spatial multi-species occupancy model using spOccupancy. This step includes:

        Model specification (detection and occupancy components)

        Prior selection

        MCMC fitting

        Diagnostics and summary of results

        Visualization of spatial patterns

Requirements

This project is written in R and uses the following key packages:

    spOccupancy

    tidyverse

    sf

    raster / terra

    ggplot2

    here

    knitr, rmarkdown
