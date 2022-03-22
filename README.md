# levee_police

### Flood Mitigation

### Description

`geo_police` offers simple open-source visualizations for geotechnical instruments for structural health monitoring.

![image](https://user-images.githubusercontent.com/43248948/143323607-f6d6ef67-86ed-4a1e-b6f2-884acb6f1ac3.png)

Go to website:
[https://resilientinfrastructure.github.io/geo_police/](geo_police website: https://resilientinfrastructure.github.io/geo_police/)


### Motivation

As flooding and climate change becomes a greater risk to coastal cities, the greater need for better levees, seawalls, and infrastructure.
For example, the city of New Orleans had catastrophic problems due to levee (one type of an embankment built to prevent the overflow of the sea/river) structural failures - read the story from Wikipedia
[https://en.wikipedia.org/wiki/2005_levee_failures_in_Greater_New_Orleans](https://en.wikipedia.org/wiki/2005_levee_failures_in_Greater_New_Orleans).

Structural integrity is crucial to protect underground infrastructure. Long term health and quality control can be achieved with adequate data monitoring. Current  Data Management Systems used in infrastructure projects cost millions of dollars to use and operate. To ensure long-term life-cycle of our infrastructure projects, structural health monitoring offers the opportunity to supervise the infrastructure works and hold involved operating and construction parties accountable during the process. There is a need a collaborative platform with servers, maps, and info-graphics built on top of existing standards to improve how we monitor public spending. 

Read more about the need for geotechnical visualizations and monitoring in this article [article](https://medium.com/data-tale/underground-version-2-0-2ce60f040245).

## Problem
Geotechnical data during construction and operation is usually late, difficult to manage, and not shared with the client in a timely manner.
Current Geotechnical Technical Data Management Systems are used in infrastructure projects and cost millions of dollars to use and operate. An open-source platform can create a scalable product that can potentially provide free visualizations*

![image](https://user-images.githubusercontent.com/43248948/143324136-085f361f-333a-47b7-b324-d3711e37f659.png)
*Figure 1. Current Geotechnical Technical Data Management Systems are used in infrastructure projects and cost millions of dollars to use and operate. An open-source platform can create a scalable product that can potentially provide free visualizations*

![image](https://user-images.githubusercontent.com/43248948/143330002-e1e29a6a-622f-4dc7-a83a-497057c9247e.png)
*Figure 2. Traditional instrumentation data visualization in Excel:

Raw sample inclinometers data can be found:
https://github.com/mv1742/levee_police/tree/master/data

## Product Idea

`Geo_police` is a platform to visualize monitoring instruments real-time. Contractors and operators should be legally obliged to provide this data to guarantee quality of the levee.

## Solution
Architecture diagram:
![Screenshot (456)](https://user-images.githubusercontent.com/43248948/159421223-ba37d187-097e-48f8-8e80-d9bdeb34af1a.png)

### Map
A dashboard using Mapbox open street maps and Power BI

### Backend
Backend in Python aggregates displacement rates and identifies anomalies.

Other possible instrumentation visualizations that can be added include
CPT, SPT, settlement markers, tiltometers...