# ANA366 - Agile Business and Data Layer Modeling with SAP Data Warehouse Cloud

## Description

Learn how the different modeling layers complement each other and allow for a new modeling experience. Get to know the benefits of the business and data layer, when to use what, and how to combine the two.

## Overview

In this session you will get to know about the new Business Layer modeling environment by implementing an end-to-end scenarios, such as *Sales Pipeline per Quarter* and *Sales Quota Coverage*. During the course of the exercises you will learn:
- how to use the new *Business Builder*
- how to associate the Business Entities
- how to define *Calculated Measures*
- how to use the *Data Preview* to analyze the result
- how to create a *Consumtion Model* and *Perspectives* 
- how to build an *SAP Analytics Cloud Story* 

![Exercise Overview](/images/exercise_overview.png)

## Requirements

1. SAP Data Warehouse Tenant:
Get a 30-Days free Trial Tenant
https://saphanajourney.com/data-warehouse-cloud/trial/
![DWC_Free_Trial](/images/FreeDWCTrial.png)

During the Teched 2020, following tenants are accessible:

Location | URL
---------|-----
US | https://dwc-teched2020.us10.hcs.cloud.sap/dwaas-ui/index.html#/home
EMEA | https://dwc-teched2020.eu10.hcs.cloud.sap/dwaas-ui/index.html#/home
APJ | https://dwc-teched2020.ap10.hcs.cloud.sap/dwaas-ui/index.html#/home

2.) Download the [CSV Test Data](/csv_dataset/DWC_BIKE_SALES_DEMO.zip) for the the exercises

3.) Create a Space 
In order to do the modeling exercises please make sure that your user has been asigned to a space.
- Navigate to Space Management and click on the 'Create Space'-Button:
  ![Create Space](/images/create_space.png)
- Enter a new Space Name
- Please make sure to reset the Disk and In-Memory size to 0.1GB.
  ![Resize Space](/images/resize_space.png)
- In the section *Member Assignment*, please add your User to the new created space.
- Please make sure that your User has been assigned with the role *DW Modeler*.

## Exercises

Provide the exercise content here directly in README.md using [markdown](https://guides.github.com/features/mastering-markdown/) and linking to the specific exercise pages, below is an example.

- [Exercise 1 - Import the Bikes Sales Dataset](exercises/ex1/)
    - [Exercise 1.1 - Import Products CSV File](exercises/ex1/README.md#exercise-11-import-products-csv-file)
    - [Exercise 1.2 - Import Sales Pipepline CSV File](exercises/ex1/README.md#exercise-12-import-sales-pipeline-csv-file)
    - [Exercise 1.3 - Import Sales Quota CSV File](exercises/ex1/README.md#exercise-13-import-sales-quota-csv-file)
     
- [Exercise 2 - Create Data Layer Models](exercises/ex2/)
    - [Exercise 2.1 - Create Products View](exercises/ex2/README.md#exercise-21-create-products-view)
    - [Exercise 2.2 - Create Sales Pipeline View](exercises/ex2/README.md#exercise-22-create-sales-pipeline-view)
    - [Exercise 2.3 - Create Sales Quota View](exercises/ex2/README.md#exercise-23-create-sales-quota-view)
    - [Exercise 2.4 - Generate Time Dimension](exercises/ex2/README.md#exercise-24-generate-time-dimension)
    
- [Exercise 3 - Create Business Layer Models](exercises/ex3/)
    - Create Dimension Product
    - Create Dimension Time Dimension - Day 
    - Create Dimension Time Dimension - Quarter
    - Create Analytical Dataset - Sales Pipeline
    - Create Analytical Dataset - Quota
    
- [Exercise 4 - Create Consumption Models](exercises/ex4/)
    - Create Consumption Model - Sales Pipeline per Quarter
    - Create Consumption Model - Sales Quota Coverage

- [Getting Started](exercises/ex0/)
- [Exercise 1 - First Exercise Description](exercises/ex1/)
    - [Exercise 1.1 - Exercise 1 Sub Exercise 1 Description](exercises/ex1#exercise-11-sub-exercise-1-description)
    - [Exercise 1.2 - Exercise 1 Sub Exercise 2 Description](exercises/ex1#exercise-12-sub-exercise-2-description)
- [Exercise 2 - Second Exercise Description](exercises/ex2/)
    - [Exercise 2.1 - Exercise 2 Sub Exercise 1 Description](exercises/ex2#exercise-21-sub-exercise-1-description)
    - [Exercise 2.2 - Exercise 2 Sub Exercise 2 Description](exercises/ex2#exercise-22-sub-exercise-2-description)


**OR** Link to the PDF document stored in your github repo for example...

Start the exercises [here](exercises/myPDFDoc.pdf).
    
**OR** Link to the Tutorial Navigator for example...

Start the exercises [here](https://developers.sap.com/tutorials/abap-environment-trial-onboarding.html).

**IMPORTANT**

Your repo must contain the .reuse and LICENSES folder and the License section below. DO NOT REMOVE the section or folders/files. Also, remove all unused template assets(images, folders, etc) from the exercises folder. 

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
