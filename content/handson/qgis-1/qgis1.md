---
layout: default
title: Outline
nav_order: 4.1
has_children: true
has_grandchildren: true
has_toc: false
---

# Understanding Spatial Data: Map Projections

## Learning Outcomes

This workshop is intended to familiarize participants with foundational knowledge for working with spatial data. By the end of the workshop participants will be able to:

- describe what a coordinate reference system is
- describe what a map projection is
- know how to find the coordinate reference system of your data
- know to how project your data into a different coordinate system
- find additional resources

## Requirements and Setup

The exercises in this workshop will use Esri's ArcGIS Desktop software, available for download from [UBC IT](http://gis.ubc.ca/software/).

If you have a Mac, it will be more challening to download ArcGIS software, which is more compatible with a Windows operating system.

Please consult this [article](https://pro.arcgis.com/en/pro-app/get-started/run-pro-on-a-mac.htm) to learn more.

Students are able to download ArcGIS Desktop for $30 a year.

If you don't want to pay to use the software, you can [sign up for a free trial](https://www.esri.com/en-us/arcgis/trial?rmedium=esri_com_redirects01&rsource=https://links.esri.com/pro/trial), although there may be a pause on free trials during the pandemic unless your work is related to COVID-19.

ArcGIS is also available on UBC Library's lab computers via VM's on a first-come-first-serve basis. Log in with your CWL to access remote labs here: [remote labs](https://remotelabs.ubc.ca).

Labs with ArcGIS:

Library Lab - Koerner Library Computer Lab (RM 217)
Library Lab - Data/GIS Lab (RM 218 A)
Library Lab - Digital Scholarship Lab (RM 497)

If none of these is an option for you and you are attending this workshop from home, you can still follow along and apply the principles learned in this workshop to the GIS software of your choice.

There will be three applications that come with your download of ArcGIS Desktop.

- **ArcCatalog**: file browser for managing and organizing your data
- **ArcMap**: program to view, edit, and analyze data and create maps
- **ArcGIS Pro**: newer program that has similar functionality to ArcMap but more 3D capability and better communication with ArcGIS Online

For the purposes of this workshop, we will only be using **ArcMap**.

You will also need to download data and 3 MXD (maps).

[Download](https://www.dropbox.com/s/945j1dffuqja8ox/gisData.zip?dl=0){: .btn .btn-blue }

Download the data and extract the compressed files into your **Downloads** folder.

## Outline

- Video introducing projections
- Coordinate Reference Systems
- Datums
- Geographic and Projected Coordinate Systems
- Map Projections
- Choosing the Right Projection
- Exercises using ArcMap
