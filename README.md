## 4. Exploratory Data Analysis Project 1

by C. Bleile

This assignment uses data from the UC Irvine Machine Learning Repository, a popular repository for machine learning datasets. In particular, we will be using the “Individual household electric power consumption Data Set” which I have made available on the course web site:

**Dataset:**
[Electric power consumption](https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip) [20Mb]

**Description:** Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

The following descriptions of the 9 variables in the dataset are taken from the UCI web site:

1. **Date:** Date in format dd/mm/yyyy
1. **Time:** time in format hh:mm:ss
1. **Global_active_power:** household global minute-averaged active power (in kilowatt)
1. **Global_reactive_power:** household global minute-averaged reactive power (in kilowatt)
1. **Voltage:** minute-averaged voltage (in volt)
1. **Global_intensity:** household global minute-averaged current intensity (in ampere)
1. **Sub_metering_1:** energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
1. **Sub_metering_2:** energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
1. **Sub_metering_3:** energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

### Usage

There are four .R scripts (plot1.R, plot2.R, plot3.R and plot4.R) that assume the data from the link above (Electric power consumption) has been downloaded and unzipped into the user's home directory.  The scripts are assumed to be colocated.  The scripts are run and individually and each results in a plot (plot1.png, plot2.png, plot3.png and plot4.png) written to the working directory.  

If the user desires, one can modify the working directory for each script to perform in a directory of their choice by replacing the "~" in each script with a working directory of their choice.  It would be trivial to make a function that accepted a WD as well.

### Plots
![alt text](https://github.com/bleile/4_ExploratoryDataAnalysisProject1/blob/main/plot1.png?raw=true)
![alt text](https://github.com/bleile/4_ExploratoryDataAnalysisProject1/blob/main/plot2.png?raw=true)
![alt text](https://github.com/bleile/4_ExploratoryDataAnalysisProject1/blob/main/plot3.png?raw=true)
![alt text](https://github.com/bleile/4_ExploratoryDataAnalysisProject1/blob/main/plot4.png?raw=true)

