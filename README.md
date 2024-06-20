# Detection of Inefficiencies in Photovoltaic Solar Plants

![featured](https://github.com/pabloelt/detection-inefficiencies-photovoltaic-solar-plants//blob/main/Datos/Imagenes/featured.jpg?raw=true)

##### Table of Contents 
* [Introduction](#introduction)
* [Objectives](#objectives)
* [Project results](#project-results)
* [Project structure](#project-structure)
* [Instructions](#instructions)

<div align="justify"> 
 
## Introduction

The client for this project is a photovoltaic solar power generation company. This company, which operates nationwide, has detected anomalous behaviors in two of its plants. However, the maintenance team cannot identify the cause of the problem.

Before dispatching a team of engineers, they have requested the data science team to analyze the sensor and performance data to identify the potential root cause of the issue.

 * [See a more detailed explanation here](https://pabloelt.github.io/project/project2/)

## Objectives

The main objective is to analyze the data from the past month for the two affected solar plants and investigate the root cause of the problem. Based on this analysis, the company will decide whether to dispatch a team of engineers to the plants or apply another solution.

## Project results

The main results obtained from this Discovery Project are summarized below:

**1. Both solar plants are receiving approximately the same amount of energy**
* The two affected solar plants are receiving approximately the same energy levels based on irradiation, ambient temperature, and temperature reached by the photovoltaic modules.
  * Irradiation is working on the modules from 7 am to 5 pm.
  * Maximum irradiation is reached from 11 am to 12 am.
  * Maximum ambient temperature is reached from 2 pm to 4 pm.

**2. The quality of the data is pretty bad**
* The amount of KW registered per day is not trustworthy in either of the two affected plants.
* The registered amounts of KW of DC and AC are also weird.

**3. Assuming that the DC and AC quantities are correct, we found that:**
* Plant 2 generates much lower levels of DC even at similar levels of irradiation.
  * Plant 1 has much more variability, while Plant 2 is more consistent.
* Plant 1 has a very low capacity to convert DC to AC.
  * The inverters in Plant 1 are not working properly.
* Plant 2 presents several inverters that are not receiving sufficient DC production.
  * The inverters in Plant 2 are working fine, so the modules need inspection. 
  
**4. Recommendations**
* Review the data collection processes and their reliability.
* Perform a maintenance inspection on the identified inverters in Plant 2, since there are many moments of zero DC generation.
* Perform a maintenance inspection of all inverters in Plant 1.

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

</div>
