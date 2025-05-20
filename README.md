This repository contains all scripts and supporting materials for the third chapter of my PhD dissertation, focusing on spatial multi-species occupancy modeling using data from camera trap surveys.
Overview

The primary goal of this chapter is to analyze carnivore occupancy patterns across multiple sites using a spatial multi-species occupancy model (spMSOM). The analysis is implemented in R using the spOccupancy package.

The repository is structured around two core RMarkdown files:

    Co-occurenece_pre-processing.Rmd
    Prepares and harmonises raw camera trap data from multiple sites. This includes:
        Creating sptaial dataframes
        Preparing layout files for detecttion history creaation
        Prepareing detecction data for detection history creation
        Extracting cpatial covatriates
        
    Co-occurence_main.Rmd
    Implements and runs a spatial multi-species occupancy model using spOccupancy. This step includes:
        Detection history matrix creation
        Spatial data matrix creation
        Effort matrix creation
        Detection matrices creation
        Covariate selection
        Model selection and comparison
        Diagnostics and summary of results
        Visualisation of spatial patterns

Requirements

This project is written in R and uses the following key packages:
    spOccupanc
    tidyverse
    sf
    terra
    ggplot2
    
