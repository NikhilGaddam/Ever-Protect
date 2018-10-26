# Ever-Protect(Flood Watcher)

## Table of Contents
1. [Project Overview](#project-overview)
1. [Project Description](#project-description)
1. [Who will benefit from this your project](#who-will-benefit-from-this-your-project)

# Project Overview
  Development of Google Flood Map (GFM) Android application for early warning of flood.
# Project Description

This project aims to develop an android application, which can be used for early warning of flood for a given area. To start with, the proposed area in this project is Guwahati city, a fast developing urban city in North East India. This application will be similar to the google traffic map, which gives a real time status of traffic congestion in a given area. The flood warning app currently developed will not be a real time warning system. To begin with, the application will give an early warning of flood scenarios in different parts of the city based on rainfall forecast. This necessitates the hydrological modelling of the given area for determining flood depth for a given rainfall intensity. The computed flood depth map can be integrated with android based flood warning in smart phone.


The entire project will employ Android Studio IDE along with ArcGIS Runtime SDK, Watershed modelling Software (WMS, US Army Corps of Engineers) and SWMM for flow modeling. The project aims to display flood inundation data and user’s location on the Google map. The App will get the current position through GPS or network provider from the user mobile phone. The App would collect 4 days Rainfall forecast from Indian Meteorological Department (IMD) based on which the flood warning will be issued. Flood inundation map (FIM) is required to understand the impact of flooding in a particular area and on important structures such as roadways, railways, streets, buildings, airport, etc. It provides important information like depth and spatial extent of flooded zones, which is required by the municipal authorities to inform the citizens about the major flood prone areas and adopt appropriate flood management strategies. FIM is determined by using WMS platform. The runoff (flow rate) obtained using SWMM was integrated with the drainage network details of the study area for determining the inundated area. Further, unsteady flow modelling in the drains is carried out by using Hydrologic Engineering Centre-River Analysis System (HEC-RAS) in WMS platform to obtain water surface elevation in the drainage channel. WMS intersects the water surface elevation data with the TIN of the study area to evaluate the flood spread. The flood spread is overlaid on the ward map of the study area to know the flood inundated zones. 

The project aims to display flood inundation data and user’s location on the Google map. The App will get the current position through GPS or network provider from the user mobile phone. There will be a server where in the flood modelling will be done based on the rainfall forecast. The output from the flood modelling, i.e., the flood inundation map will be displayed in different colour scheme to show the extend of flooding in a given area.With network of rain gauges deployed in a given area, this application can be extended to near real time flood forecasting. This will be future work of the proposed project.


## Who will benefit from this project?

  Though almost all districts in Assam are a flood-prone area,People in areas close to Bramhaputra river and some other low lying areas will benifit a lot by taking precautions and prepare themselves from a flood. 
