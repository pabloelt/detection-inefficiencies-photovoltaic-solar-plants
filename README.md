# Detection of Inefficiencies in Photovoltaic Solar Plants

![featured](https://github.com/pabloelt/detection-inefficiencies-photovoltaic-solar-plants//blob/main/Datos/Imagenes/featured.jpg?raw=true)

##### Table of Contents 
* [Introduction](#introduction)
* [Objectives](#objectives)
* [Project results](#project-results)
* [Project structure](#project-structure)
* [Instructions](#instructions)


## Introduction

The client for this project is a real estate company that invests in large cities by purchasing properties to rent out as vacation apartments. The managers have decided to invest in Madrid and are interested in analyzing publicly available data from the sector leader, Airbnb, to identify the types of properties with the greatest commercial potential for vacation rentals.

As the main deliverable, the management expects to receive a detailed typology of properties that the valuation team should target among the existing opportunities in the city, as well as the primary neighborhoods or geographic areas to focus on.

 * [See a more detailed explanation here](https://pabloelt.github.io/project/project2/)

## Objectives

The main objective is to identify the property profiles with the highest potential in the vacation rental market. This can guide the valuation team on where to start looking for such opportunities and highlight the key neighborhoods and geographical areas, which are most promising to focus on.

This analysis is primarily conducted in terms of rental prices, occupancy levels, and purchase prices. 

## Project results

The main results obtained from this Discovery Project are summarized below:

**1. Ten neighborhoods with a high investment potential have been identified**
* They can be segmented into 4 groups depending on the type, quality, and property location.
* These 4 groups, which have been identified, are the following:
  * *Low cost Investment*: Simancas, Ambroz, Marroquina, San Juan Bautista.
  * *Medium cost investment*: El Plantio, Valdemarín, Valdefuentes.
  * *Medium-high cost investment*: Jerónimos, Fuentela reina.
  * *High cost investment*: Recoletos.

**2. It is recommended to search for two-bedroom properties that can accommodate 4 guests**
* The number of guests that maximize the rental price while minimizing the property's purchase price is 4.

**3. It is recommended to search for properties in one of the identified neighborhoods that are not necessarily close to points of interest**
* These properties are expected to have a lower purchase price.
* It seems that proximity to points of interest does not have a particular impact on rental prices.
  
**4. A new business model based on rentals for specific moments of high sporting interest should be explored**
* It is advisable to look for opportunities in the San Blas neighborhood.
* These properties present a particularly high cost-income ratio per night.
* There are still many rentals that are not exploiting this potential.

## Project structure

* 📁 Datos: Project datasets.
  * 📁 Imagenes: Contains project images.
* 📁 Notebooks:
  * <mark>01_Diseño del proyecto.ipynb</mark>: Notebook compiling the initial design of the project.
  * <mark>02_Calidad de datos y creacion datamart analitico.ipynb</mark>: Notebook analyzing the quality of the data and creating the analytic data mart (loading and unifying data, applying data quality processes, and so on).
  * <mark>03_Transformacion de datos.ipynb</mark>: Feature engineering and data transformation notebook.
  * <mark>04_Analisis e Insights.ipynb</mark>: Notebook used for the execution of the exploratory data analysis, which collects the business insights and the recommended actionable initiatives.

## Instructions

* Remember to update the <mark>project_path</mark> to the path where you have replicated the project.
