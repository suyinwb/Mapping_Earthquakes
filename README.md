# Mapping Earthquakes

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

Your approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. You'll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

Before you add your folders and files to the Mapping_Earthquakes folder, Basil would like you to create a GitHub branch for the basic map. Basil informs you that creating a branch off the main branch allows you to create a new feature, or change some part of the original code. Once he has reviewed your code on your branch, Sadhana will show you how to merge it with the main branch.

Mapbox provides custom maps for websites and applications such as Strava, Facebook, the Financial Times, The Weather Channel, Snapchat, and Instacart. Since October 2019, Mapbox has been generating up to 14 billion individual sensor readings daily across 100,000 map updates on connected devices.



## Background


## Overview of Project


### Purpose


## Analysis And Challenges

## Methodology: Analytics Paradigm

#### 1. Decomposing the Ask


#### 2. Identify the Datasource


### 3. Define Strategy & Metrics
**Resource:** Javascript, CSS, HTML, Data-Driven Documents (D3) library, Leaflets.js, API, GeoJSON,

#### 4. Data Retrieval Plan

#### 5. Assemble & Clean the Data

#### 6. Analyse for Trends


#### 7. Acknowledging Limitations


#### 8. Making the Call:
The "Proper" Conclusion is indicated below on [Summary](#summary)

## Analysis


>Bar & Gauge Charts

![Bar & Gauge Charts](resources/bar_gauge_charts.png)


>Bubble Chart

![Bubble Chart](resources/bubble_chart.png)


## Summary



## Appendix

Changing the map's style

``` js
mapbox/streets-v11
mapbox/outdoors-v11
mapbox/light-v10
mapbox/dark-v10
mapbox/satellite-v9
mapbox/satellite-streets-v11
```
----

How to create new branch in terminal

1. Confirm you're in main branch with the latest files with the commands below:
```
git branch
git checkout main
git pull
```
2. Create new branch with the files above
```
git checkout -b [name_of_your_new_branch]
```
----

Setup push to branch with the command below and later work as usual in this branch
```
git push --set-upstream origin Simple_Leaflet_Map
```
