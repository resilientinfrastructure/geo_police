# geo_police


### Description

`geo_police` offers simple visualizations and analytics for geotechnical instruments for structural health monitoring.

![image](https://user-images.githubusercontent.com/43248948/143323607-f6d6ef67-86ed-4a1e-b6f2-884acb6f1ac3.png)

Go to website POC:
geo_police [website](https://resilientinfrastructure.github.io/geo_police/)

### Motivation
Structural integrity is crucial to protect underground infrastructure. Long term health and quality control can be achieved with adequate data monitoring.

Read more about the need for geotechnical visualizations and monitoring in this article [article](https://medium.com/data-tale/underground-version-2-0-2ce60f040245).

## Problem
**Geotechnical data is usually incomplete and delivered late to clients**.

Current Geotechnical Technical Data Management Systems used in infrastructure projects cost millions of dollars. Modern data tools like real-time monitoring, dashboards, and data science provide the opportunity to improve the way we operate infrastructure projects. An open-source tool can provide value for all parties involved.

<figure>
<img src="https://user-images.githubusercontent.com/43248948/143324136-085f361f-333a-47b7-b324-d3711e37f659.png" alt="Trulli" style="width:50%">
<figcaption align = "center"><b>Figure 1. Current Geotechnical Technical Data Management Systems are used in infrastructure projects and cost millions of dollars to use and operate. An open-source platform can create a scalable product that can potentially provide free visualizations</b></figcaption>
</figure>

## Product Idea

`Geo_police` is a platform to visualize structural and geotechnical monitoring instruments real-time. This way contractors and operators can improve their deliverables and guarantee better quality of structures.

## Solution
Possible architecture involves
1) Individual instrument data in raw format .csv, .json, .xlsx provided by the contractor, operator, or any other groundwork party.
2) Data processing with Python - aggregation, anomaly detection, etc.
3) PowerBI / Flask Data Visualizations

<figure>
<img src="https://user-images.githubusercontent.com/43248948/159421223-ba37d187-097e-48f8-8e80-d9bdeb34af1a.png" alt="Trulli" style="width:50%">
<figcaption align = "center"><b>Possible architecture diagram</b></figcaption>
</figure>

### Tools:
#### Map
A dashboard using Mapbox open street maps and Power BI.

#### Backend
Backend in Python aggregates displacement rates and identifies anomalies.

#### Other
Other possible instrumentation visualizations that can be added include:
CPT, SPT, settlement markers, tiltometers...
