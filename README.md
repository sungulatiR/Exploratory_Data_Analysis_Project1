# Exploratory_Data_Analysis_Project1
This assignment uses data from the UC Irvine Machine Learning Repository, a popular repository for machine learning datasets. In particular, we will be using the "Individual household electric power consumption Data Set" which I have made available on the course web site:
•	Dataset: Electric power consumption [20Mb]
•	Description: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.
The following descriptions of the 9 variables in the dataset are taken from the UCI web site:
1.	Date: Date in format dd/mm/yyyy
2.	Time: time in format hh:mm:ss
3.	Global_active_power: household global minute-averaged active power (in kilowatt)
4.	Global_reactive_power: household global minute-averaged reactive power (in kilowatt)
5.	Voltage: minute-averaged voltage (in volt)
6.	Global_intensity: household global minute-averaged current intensity (in ampere)
7.	Sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
8.	Sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
9.	Sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.
Loading the data
When loading the dataset into R, please consider the following:
•	The dataset has 2,075,259 rows and 9 columns. First calculate a rough estimate of how much memory the dataset will require in memory before reading into R. Make sure your computer has enough memory (most modern computers should be fine).
•	We will only be using data from the dates 2007-02-01 and 2007-02-02. One alternative is to read the data from just those dates rather than reading in the entire dataset and subsetting to those dates.
•	You may find it useful to convert the Date and Time variables to Date/Time classes in R using the strptime() and as.Date() functions.
•	Note that in this dataset missing values are coded as ?.
Making Plots
Our overall goal here is simply to examine how household energy usage varies over a 2-day period in February, 2007. Your task is to reconstruct the following plots below, all of which were constructed using the base plotting system.
First you will need to fork and clone the following GitHub repository: https://github.com/sungulatiR/Exploratory_Data_Analysis_Project1
For each plot you should
•	Construct the plot and save it to a PNG file with a width of 480 pixels and a height of 480 pixels.
•	Name each of the plot files as plot1.png, plot2.png, etc.
•	Create a separate R code file (Plot1.R, Plot2.R, etc.) that constructs the corresponding plot, i.e. code in Plot1.R constructs the plot1.png plot. Your code file should include code for reading the data so that the plot can be fully reproduced. You should also include the code that creates the PNG file.
•	Add the PNG file and R code file to your git repository
When you are finished with the assignment, push your git repository to GitHub so that the GitHub version of your repository is up to date. There should be four PNG files and four R code files.
The four plots that you will need to construct are shown below.

Plot1


![image](https://github.com/sungulatiR/Exploratory_Data_Analysis_Project1/assets/122589275/6d54020f-05f2-4e8b-a85c-51e73f33a00a)




Plot 2

![image](https://github.com/sungulatiR/Exploratory_Data_Analysis_Project1/assets/122589275/b695c444-2df3-46b4-8ac4-4c18c846a8dd)




Plot 3


![plot3](https://github.com/sungulatiR/Exploratory_Data_Analysis_Project1/assets/122589275/e6f87aac-4c6e-4fa0-b33c-9cc62c81508b)



Plot 4


![plot4](https://github.com/sungulatiR/Exploratory_Data_Analysis_Project1/assets/122589275/8eda20e5-1849-4ab1-aa7a-e93089ef8ba3)




