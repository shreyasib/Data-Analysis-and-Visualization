# Miami 311 Service Request Dataset

Data Source: https://datahub-miamigis.opendata.arcgis.com/datasets/6acb8f4ed62c4d248e0cd244f761ca25_0/about

#### Data Cleaning, Analysis and Visualization
#### Libraries: pandas, numpy, matplotlib, seaborn

## Introduction

The dataset contains service request activity for Miami. It includes services completed proactively by different departments and requests submitted by citizens via phone(311), and other self service channels.



## Data Cleaning & Manipulation
1. Drop unneeded columns
2. Check for missing values
3. Check for duplicates
4. Create and Split columns
5. Fix data types
6. Check for invalid data

## Data Analysis & Visualizaion
1. Which days in the week typically report high service requests?
2. Which month received the highest service requests?
3. Which year received the highest service requests?
4. What is the average goal time set for the service requests?
5. How long does it actually take to complete the service requests?
6. What is the trend between goal days and actual days to complete the service requests?
7. What are the most requested issues?
8. Which Case owners receive the most service requests?
9. Which Ticket priority receives the most service requests?
10. What are the common methods to request a service?

## Key Findings
* Tuesday has the highest number of tickets followed by Thursday and Wednesday.
* October has the highest number of service requests
* 2022 has the highest number of servie requests
* Most tickets have goal days set as below 20 days.
* Most tickets are actually completed under 10 days.
* The most common issue type is GARCONDM.
* Solid Waste is the most common type of issue case owner.
* The Standard priority ticket is the most common one.
* Phone is the most common method to request for services. 

## Strategic Recommendations
After the analysis, we share our high-level business recommendations:

1. Implement a system for tracking and monitoring service requests. This could include setting up a system for assigning service request numbers, establishing a timeline for resolution, and providing regular updates to residents about the status of their request.
2. Consider implementing a system for soliciting feedback and suggestions from residents about how to improve the 311 service. This could help identify areas where the service could be improved, and help ensure that it is meeting the needs of the community.
