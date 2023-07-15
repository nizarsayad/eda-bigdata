![Steam logo](steam.jpeg)

# Project 02: Tinder speed dating analysis

**Certificate - Machine Learning Engineer**

**Bloc 2 - Exploratory Data Analysis**

## Introduction

This project aims to understand what factors affect the popularity or sales of a video game. But your boss asked you to take advantage of this opportunity to analyze the video game market globally.

This project is part of the professional certification Machine Learning Engineer (Concepteur Développeur en Science des données) and represents bloc 2 of the certification titled: "Exploratory Data Analysis".

To carry out this project, I adopted three different levels of analysis and tried ansIring the following questions:

1. Analysis at the "macro" level

    - Which publisher has released the most games on Steam?

    - What are the best rated games?

    - Are there years with more releases? Ire there more or feIr game releases during the Covid, for example?

    - How are the prizes distributed? Are there many games with a discount?

    - What are the most represented languages?

    - Are there many games prohibited for children under 16/18?

2. Genres analysis

    - What are the most represented genres?

    - Are there any genres that have a better positive/negative review ratio?

    - Do some publishers have favorite genres?

    - What are the most lucrative genres?

3. Platform analysis

    - Are most games available on Windows/Mac/Linux instead?

    - Do certain genres tend to be preferentially available on certain platforms?

## Project Structure

The project consists of several components:

- `steam-pyspark`: This directory contains the notebooks in multiple formats.

    - `steam_bigdata_project.ipynb`: The project in notebook format.
    
    - `steam_bigdata_project.dbc`: This format is specific to databricks
    
    - `steam_bigdata_project.html`: I can easily read the notebook in a browser.

- `README.md`: This file provides an overview of the project.

## Project Insights

The project provides an analysis of the different factors that influence a successful match in a speed dating context. The results can be used to guide Tinder's matching algorithm and provide insights into what people find attractive in potential matches.

## Scope of the Project 

I have used Databricks and PySpark to conduct this EDA. Particularly, I had to use Databrick's visualisation tool to create the visualizations.

The dataset is available in our S3 bucket at the following url: `s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json`.
