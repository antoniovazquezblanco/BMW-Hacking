---
layout: default
title: KISWB
permalink: /general_info/psdz_data/kiswb
parent: PSdzData
nav_order: 1
---

# KISWB

_PSdzData_ has many many components. Inside _PSdzData_ folder structures you may find some folders named _KISWB_. The _KIS_ portion of the name stands for something similar to compatibility and information system and _WB_ portion of that name comes from WissensBasis that means knowledge base in English.

The files contained inside _KISWB_ are HSQL databases. These files can be opened using any HyperSQL DataBase client. Currently, my recommended tool to work with KISWB databases is [DBeaver](https://dbeaver.io/download/).

## Browsing KISWB

In order to open a KISWB download and install [DBeaver](https://dbeaver.io/download/). Open the program and click on the new database connection button.

![New database connection](PSdzData_KISWB_NewDatabase.png)

From the option list select HSQL Embedded option and click on _Next_.

![New database connection](PSdzData_KISWB_DatabaseSelection.png)

Select the folder path of the KISWB database you want to browse. Also, make sure you append the _KIS_ file name at the end. Clock on Finish.

![New database connection](PSdzData_KISWB_DatabasePath.png)

You may now browse the database contents.

## KISWB Tables

A summary of the tables contained in a KISWB database can be found below:

| Table              | Description                                                                                                                                                |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRV                | Lists the main series (Baureihe Verbund) in the database.                                                                                                  |
| EBR                | Lists Entwicklungscodes (Development Codes) and shows its relationship with the BRV table (Baureihe Verbund - Main series).                                |
| FAHRZEUGTYP        | Lists Fahrzeugtyp (Vehicle types) and its correlation to EBR (Entwicklungscodes - Development Codes).                                                      |
