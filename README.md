# Complaints US Gov Dataset Analysis
The code and the results of the DW and Data Mining tasks performed on the [US Government's public dataset](https://www.consumerfinance.gov/data-research/consumer-complaints/) about Consumer Complaints.

A simple presentation of the project and its results (in Greek) can be found [here](https://www.slideshare.net/NikiforosBotis/consumer-complaints-analyzing-an-us-governments-dataset?ref=https://www.slideshare.net/NikiforosBotis/slideshelf).

The analysis of the particular dataset included the following steps:

1. The data included in the dataset was modeled in order to be efficiently stored and depicted and according to that, a Data Warehouse (DW) was created making use of the MS SQLServer platform.
2. The contents of the dataset were inserted into the DW using both the import wizard and SQL statements for achieving that.
3. A cube was created and deployed on the MS Visual Studio "above" the existing DW.
4. The data mining tasks were performed using the tables of the DW.
5. Tableau was connected with the cube (Step 3) and it was used as the tool in which the OLAP analysis took place.
6. Two Map/Reduce jobs were performed on particular data of the dataset.
