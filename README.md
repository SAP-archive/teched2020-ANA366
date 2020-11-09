# ANA366 - Agile Business and Data Layer Modeling with SAP Data Warehouse Cloud

## Description

Learn how the different modeling layers complement each other and allow for a new modeling experience. Get to know the benefits of the business and data layer, when to use what, and how to combine the two.

## Overview

In this session you will get to know about the new Business Layer modeling environment by implementing end-to-end scenarios, such as **Sales Pipeline per Quarter** and **Sales Pipeline Coverage**. During the course of the exercises you will learn:
- how to create new Business Entitities
- how to associate the Business Entities
- how to define *Calculated Measures*
- how to use the *Data Preview* to analyze the result
- how to create a *Consumtion Model* and *Perspectives* 
- how to build an *SAP Analytics Cloud Story* 

![Exercise Overview](/images/exercise_overview.png)

## Prerequisites
Before you can start with the exercises, please make sure the following:

### 1. Get the test dataset
Please download the [CSV Test Data](/csv_dataset/DWC_BIKE_SALES_DEMO.zip) for the the exercises.

### 2. Get an SAP Data Warehouse Tenant:
For during the TechEd 2020 event on the 10th December 2020, there will be dedicated server provided for the regitered participats
Please contact your session instructors for more detailed login informations.


Location | URL
---------|-----
US | https://dwc-teched2020.us10.hcs.cloud.sap/dwaas-ui/index.html#/home
EMEA | https://dwc-teched2020.eu10.hcs.cloud.sap/dwaas-ui/index.html#/home
APJ | https://dwc-teched2020.ap10.hcs.cloud.sap/dwaas-ui/index.html#/home


**After the TechEd event** the tenants won't be available. For that you can apply for a **30-Days free Trial Tenant** under the following link:
https://saphanajourney.com/data-warehouse-cloud/trial/
![DWC_Free_Trial](/images/FreeDWCTrial.png)


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

Please download the exercise 1 *Sales Pipeline per Quarter*: [ANA366_BL_Modeling_Exercise_1.pdf](exercises/ANA366_BL_Modeling_Exercise_1.pdf).

Please download the exercise 2 *Sales Pipeline Coverage*: [ANA366_BL_Modeling_Exercise_1.pdf](exercises/ANA366_BL_Modeling_Exercise_1.pdf).


**IMPORTANT**

Your repo must contain the .reuse and LICENSES folder and the License section below. DO NOT REMOVE the section or folders/files. Also, remove all unused template assets(images, folders, etc) from the exercises folder. 

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
