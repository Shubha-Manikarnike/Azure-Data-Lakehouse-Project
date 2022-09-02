# Azure-Data-Lakehouse-Project
Build a Data Lakehouse solution for Divvy Bikeshare.

Divvy is a bike sharing program in Chicago, Illinois USA that allows riders to purchase a pass at a kiosk or use a mobile application to unlock a bike at stations around the city and use the bike for a specified amount of time. The bikes can be returned to the same station or to another station. The City of Chicago makes the anonymized bike trip data publicly available for projects like this where we can analyze the data.

The goal of this project is to develop a data lake solution using Azure Databricks using a lake house architecture. The key items of the project are

1. Design a star schema based on the business outcomes listed below;
Import the data into Azure Databricks using Delta Lake to create a Bronze data store;
2. Create a gold data store in Delta Lake tables;
Transform the data into the star schema for a Gold data store;


The repository consists of a 
1. PDF file showing the ER diagram of the Star Schema.
2. An Azure Databricks notebook which contains creation of Bronze, Silver and Gold Layers.
