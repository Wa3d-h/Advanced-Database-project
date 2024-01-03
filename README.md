# Advanced-Database-project (Blood Bank System)
## Scenario
A database for the management of the blood
bank system focusing on the management of
the staff to record the data of donors and
patientsThe managers dealt with the requests of
patients and hospitals by giving orders
according to blood samples
By using this system searching the available
blood becomes easy and saves lot of time than
the manual system. It will hoard, operate,
recover and analyze information concerned
with the administrative and inventory
management within a blood bank. This system
is developed in a manner that it is manageable,
time effective, cost effective, flexible and
much man power is not required
## Database Planning
The administration exercises that permit the phases of
the information base framework advancement
lifecycle to be acknowledged as proficiently and
viably as could be expected under the circumstances.
A significant initial phase in information base
arranging is to characterize the statement of
purpose for the information base framework.

### The mission statement
characterizes the significant points of the information base framework.

### Mission objective
ought to distinguish a specific undertaking that the information base framework must help.

## System Definition
Describes scope and boundaries of database system and the major user views.

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/898087ab-e2ec-4166-a9db-8e606cd1da12" width="500">

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/c7143c2e-3c5f-4f47-b4c5-6b50dffb8c37" width="500">

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/95e9e0f5-0a83-40af-a43e-cc7877e92dd0" width="500">

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/2ef27074-f0ec-4a25-9914-8d894e3a1afc" width="500">

## Conceptual database design (ER)

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/a88ddcfc-d812-4796-893a-b938e14228ce" width="500">

## ER MAPPING SCHEMAS

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/cdece1f7-eb3c-43ff-9e2d-a82093aebcf1" width="500">

## RELATIONSHIP BETWEEN ENTITIES

### 1.Staff and Donor:
Relationship = “registers”
Type of relation = 1 to many
Explanation = One recording staff can register many donors.
One donor will register with one recording officer.
The relationship with Recording staff and Donor is 1 to many.
That’s why primary key of Recording staff is used as a foreign key in Donor
### 2. Staff and patients:
Relationship =“record”
Type of relation = 1 to many
Explanation = One recording staff can record many patients. Onepatient will be
recorded by one recording staff.
The relationship with staff and patients is 1 to many.
That’s why primary key of staff is used as a foreign key in patients.
### 3. patients and Manager:
Relationship =“requests in ”
Type of relation = 1 to many
Explanation = One patients can request blood to one manager and
one manager can handle requests from many patients.
The relationship with Blood Bank Manager and patients is 1 to
many. That’s why primary key of Blood Manager is used as a foreign key in patients
### 4. Hospital and Manager:
Relationship =“gives order ”
Type of relation = 1 to many
Explanation = One Blood bank manager can handle and process
requests from many hospitals. One hospital will place request to on blood bank manager
The relationship with Blood Bank Manager and Hospital info is 1 to many.
That’s why primary key of Blood Bank manager is used as a foreign key in Hospital info.
### 5. Manager and Blood Specimen:
Relationship =“deales with ”
Type of relation = 1 to many
Explanation = One Blood bank manager can manage many blood
specimen and one specimen will be managed by one manager.
The relationship with Blood Bank manager and Blood Specimen is 1 to many.
That’s why primary key of Blood Bank manager is used as a foreign key in Blood Specimen

## Logical database Design

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/0c0ad301-26c3-4f01-866f-52d763315141e" width="500">

## Physical database Design

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/d72ad6d6-266f-4b40-b3f5-0e444cfcb8c3" width="500">

## DBMS selection

### 1- Determine and study requirements:

<img src="https://github.com/Wa3d-h/Advanced-Database-project/assets/102664990/a88ddcfc-d812-4796-893a-b938e14228ce" width="500">

### 2- shortlist two or three products:
- MySQL
- MongoDB
- Amazon Simple Storage Service (S3)
- Elasticsearch

### 3-evaluate products:
1. MySQL
2. MongoDB
3. Amazon Simple Storage Service (S3)
4. Elasticsearch
5- recommend selection and produce report: 











