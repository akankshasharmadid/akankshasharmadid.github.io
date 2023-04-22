---
title: "Seattle Crash Data Severity Predictor"
excerpt: "Seattle implemented a Vision Zero initiative in 2015 with the goal of eliminating traffic deaths and serious injuries on city streets by 2030. However, in the past two years, deaths and serious injuries from traffic collisions have been on the rise, indicating that current initiatives may not be enough. The project aims to use Seattle's collision dataset to analyze different factors that could inform street redesigns or alternative modes of transit programs.<br/>"

---


- [Github Code Repository](https://github.com/seattlelizzard/CrashSeattle)


## Seattle Crash Data Severity Predictor

In 2015 Seattle created a “Vision Zero” plan to eliminate “traffic deaths and serious injuries on city streets by 2030” (City of Seattle). Vision Zero is an “international street safety movement”  (City of Seattle) that aims to prevent traffic collisions through a “safe system approach” (Vision Zero Network). The city of Seattle has adopted this approach, which emphasizes several aspects of traffic safety including controlling speeding and creating safer streets. However, in the past two years since 2022 “deaths and serious injuries from traffic collisions in Seattle have been trending up” (KUOW). This indicates that the Vision Zero initiatives implemented so far are not enough. For example, Seattle has had a 25-mile-per-hour speed limit on all arterial streets since 2020, but traffic deaths have continued to rise. Speed limits and speeding are one of the leading factors in the severity of collisions (City of Seattle), but other factors including weather, vehicle count, light condition, road condition, and location could impact collision severity. While not all of these factors are under human control, understanding the bigger picture could inform initiatives like street redesigns or programs to help people take alternative modes like transit. This project will use the City of Seattle’s collision dataset to analyze these different factors. 

## Table of contents
- [Seattle Crashdata Severity Predictor](#seattle-crashdata-severity-predictor)
- [Table of contents](#table-of-contents)
- [Dataset](#dataset)
- [Modeling Question](#modeling-question)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Required Packages](#required-packages)
- [Slides](#Slides)
- [Citations](#Citations)
- [Authors](#authors)



## Dataset
[(Back to top)](#table-of-contents)


The data is from the City of Seattle and includes information about crashes and weather at the time of the crash. 
[Collision Data from Seattle.gov site](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::sdot-collisions-all-years/explore?location=47.641550%2C-122.345216%2C19.74&showTable=true)

To learn more about the dataset, please see this pdf.

[Dataset description](https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf)


## Modeling Question
[(Back to top)](#table-of-contents)

We will be conducting a classfication analysis on our data to try and predict the number of collisions of a given severity. We will be analyzing  variables with a mix of continuous and categorical values:


## Methods Used
[(Back to top)](#table-of-contents)

* Data Visualization    
* Data Imputation
* Predictive Modeling
* Multi-Class Classification
* Random Search Cross Validation
* Lasso and Ride
* Regression
* Random Forest Tree


## Technologies
[(Back to top)](#table-of-contents)

* Python
* Google Colab
* Jupyter Notebooks

## Required Packages
[(Back to top)](#table-of-contents)

* Follium Library
* graphviz
* Matplotlib
* missingno
* Pandas
* seaborn
* sikit learn/scipy

## Slides
[(Back to top)](#table-of-contents)
https://docs.google.com/presentation/d/1kAawtXqGnNrwvD4Z__psvvKu8f412nrxfHE3C1fIaMM/edit?usp=sharing

## Citations
[(Back to top)](#table-of-contents)

 Anderson, Hans and Denkman, Libby. “Even with Vision Zero, traffic fatalities remain high in Seattle.” KUOW, https://www.kuow.org/stories/even-with-vision-zero-traffic-fatalities-remain-high-in-Seattle. Accessed 15 October 2022.
City of Seattle, Department of Transportation. Collisions- All Years. City of Seattle, n.d. https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf 
City of Seattle, Department of Transportation. 2021 Traffic Report. City of Seattle, February 2022. 
“Demystifying the Safe Systems Approach.”  Vision Zero Network, https://visionzeronetwork.org/resources/demystifying-the-safe-system-approach/. Accessed 15 October 2022.
“Speed Limits.” City of Seattle, https://www.seattle.gov/transportation/projects-and-programs/safety-first/vision-zero/speedlimits. Accessed 15 October 2022. 
“Vision Zero.” City of Seattle, https://www.seattle.gov/transportation/projects-and-programs/safety-first/vision-zero. Accessed 15 October 2022. 
