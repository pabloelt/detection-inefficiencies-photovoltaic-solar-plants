# Detection of Inefficiencies in Photovoltaic Solar Plants

![featured](https://github.com/pabloelt/detection-inefficiencies-photovoltaic-solar-plants//blob/main/Datos/Imagenes/featured.jpg?raw=true)

##### Table of Contents 
* [Introduction](#introduction)
* [Objectives](#objectives)
* [Project results](#project-results)
* [Project structure](#project-structure)
* [Instructions](#instructions)


## Introduction

The client for this project is a photovoltaic solar power generation company. This company, which operates nationwide, has detected anomalous behaviors in two of its plants. However, the maintenance team cannot identify the cause of the problem.

Before dispatching a team of engineers, they have requested the data science team to analyze the sensor and performance data to identify the potential root cause of the issue.

 * [See a more detailed explanation here](https://pabloelt.github.io/project/project2/)

## Objectives

The main objective is to analyze the data from the past month for the two affected solar plants and investigate the root cause of the problem. Based on this analysis, the company will decide whether to dispatch a team of engineers to the plants or apply another solution.

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
