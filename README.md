## Customer Segmentation with K-mean Clustering

Problem: 
A client in the telecommunications industry has a pre-paid price plan that offers different calling rates depending on
the subscriber location and time of day when the call is made. The varying rate is achieved by applying a variable
discount to the base call rate of R2.50. Discounts are applied per cell tower, so all subscribers calling at the same
time on a cell receive the same discount for that time slot. The original intention of the price plan was to provide
cheaper rates where there was spare capacity on the cell, however there is potential to use the functionality for
more strategic marketing ventures with the aim of growing revenue, minutes of use and/or market share.

Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.

### Data
This is the comminication call details which was collected throught different cell towers located in 9 provinces in South Africa. It is an hourly data collection for 24 hours for the period of three month. 

### Features
1. Cellclassification --- cell tower name, technology, clustertype, provinces
2. cellsVec	 - Cell Names corresponding to the dataMatrix variables.
3. timestampVec	 - Timestamps corresponding to the dataMatrix variables.
4. onnetDurMatrix	 - Total minutes of use per cell, per hour.
5. onnetRevMatrix	 - Total revenue of use per cell, per hour.
6. onnetDiscMatrix	 - Discount applied per cell, per hour.
7. erlangCombMatrix - Total combined erlang per cell, per hour
8. capacity2Matrix	 - Total available capacity per cell, per hour.

For this project we'll attempt to predict which channel each cell tower belongs to, so we won't look at this column until after we've segmented the data using clustering techniques.
Instructions

This project requires Python 2.7. All of the libraries used in this project are included in the Anaconda distribution of Python, it is highly suggested that you use Anaconda to manage packages and environments for data science with Python.

When you're ready, fire up the notebook.
