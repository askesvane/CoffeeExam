# Exploring the Spatial Aspect of Coffee Production

## The Repository

This repository contains all data, pre-processing and manipulation steps along with analysis and visualisations for the paper 'Exploring the Spatial Aspect of Coffee Production'. The paper along with the content of this repository constitutes the final exam project of 'Spatial Analytics'. The course is a part of the supplementary elective package [Cultural Data Science](https://bachelor.au.dk/tilvalg/culturaldatascience/) at Aarhus University.

## The Research Project

With the multitude of factors influencing the taste of coffee enjoyed by millions around the world, the current study seeks to investigate the geographical influence on the flavor profile. Using an extensive data set containing coffee ratings on several parameters (including acidity, balance and aroma) as well as the geographical locations of the specific coffee farms, we investigate the spatial influence on the taste experience.

__Contribution__<br>
This assignment was written as a group project between Hanna Janina Matera (au603273) and Aske Svane Qvist (au613522), where:

> Both authors contributed equally to every element of the paper: From initial conception, through data pre-processing, analysis and visualisations, to writing of the final paper and structuring of the GitHub repository. (50/50%)

## The Data

The data used in the following study was found on the online service [Kaggle](https://www.kaggle.com/datasets) and can be downloaded from the open GitHub repository [here](https://github.com/jldbc/coffee-quality-database). The dataset comprises reviews of 1340 different Arabica and Robusta coffees given by trained reviewers. The reviews were scraped from the online coffee-rating service Coffee Quality Institute (CQI) and contained various information about each coffee type such as aroma, flavor, aftertaste, acidity, body, balance, etc. The geographical coordinates were subsequently added by manually retrieving them from Google Maps.

## Repository structure and files
This repository has the following directory structure:

| Column | Description|
|--------|:-----------|
```data```| A folder containing a csv-file with the coffee data as well as shapefiles with polygons of all countries in the world.
```maps``` | Contains the interactive world maps provided as html-files. In order to open them, please clone the repository.
```CoffeeAnalysis.Rmd```| The R script containing code for all data pre-processing, analysis and visualisations. Additionally, all packages required to run the script are provided.
```README.md``` | This readme file.



