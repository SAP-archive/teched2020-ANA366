# ANA366 - Agile Business and Data Layer Modeling with SAP Data Warehouse Cloud

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2020-ANA366)](https://api.reuse.software/info/github.com/SAP-samples/teched2020-ANA366)

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
For the exercises we have prepared a set of test data in CSV format, which we are going to use during the course of this workshop.
Please download zipped test dataset via the following link: [DWC_BIKE_SALES_DEMO.zip](/csv_dataset/DWC_BIKE_SALES_DEMO.zip).

[![DWC_BIKE_SALES_DEMO.zip](/images/csv_test_data.png)](/csv_dataset/DWC_BIKE_SALES_DEMO.zip)

### 2. Get an SAP Data Warehouse Tenant:
2.1) **During the TechEd 2020 event on the 10th December 2020**, there will be dedicated tenants provided for registered participants.
**Please contact your instructor of the workshop to get access to the SAP DWC tenant**.

Location | URL
---------|-----
US | https://dwc-teched2020.us10.hcs.cloud.sap/dwaas-ui/index.html#/home
EMEA | https://dwc-teched2020.eu10.hcs.cloud.sap/dwaas-ui/index.html#/home
APJ | https://dwc-teched2020.ap10.hcs.cloud.sap/dwaas-ui/index.html#/home



2.2) **After the TechEd event** the tenants won't be available. For that you can apply for a **30-Days free Trial Tenant** under the following link:
https://saphanajourney.com/data-warehouse-cloud/trial/

[![DWC_Free_Trial](/images/FreeDWCTrial.png)](https://saphanajourney.com/data-warehouse-cloud/trial/)

### 3. Create a Space 
Each user shall create his own space, where he can work on the exercises:

- Navigate to Space Management and click on the 'Create Space'-Button
  ![Create Space](/images/create_space.png)
- Enter a new Space Name should be same as your User, which you can get from your instructor during the workshop, e.g.: **ANA366_060**
  ![Rename Space](/images/rename_space.png)

- Please make sure to reset the Disk and In-Memory size to 0.1GB.
  ![Resize Space](/images/resize_space.png)
- In the section *Member Assignment*, please add your User, e.g., **ANA366_060**
  ![Add User to Space](/images/add_user_to_space.png)
- Click on the SAVE Button to confirm your space configuration. 
  ![Save Space](/images/save_space.png)

## Exercises
Please download the exercises from here:

Exercises | Link
---------|-----
Exercise 1 *Sales Pipeline per Quarter* | [ANA366_BL_Modeling_Exercise_1.pdf](exercises/ANA366_BL_Modeling_Exercise_1.pdf) [![](/images/pdf_icon2.png)](exercises/ANA366_BL_Modeling_Exercise_1.pdf)
Exercise 2 *Sales Pipeline Coverage* | [ANA366_BL_Modeling_Exercise_2.pdf](exercises/ANA366_BL_Modeling_Exercise_2.pdf) [![](/images/pdf_icon2.png)](exercises/ANA366_BL_Modeling_Exercise_2.pdf)


## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
