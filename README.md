# Multivariate Time series Data sets

In this githup repo, we provide four data sets could be used for researches related to the multivariate time series signals. The format is same for the different datasets. Assumed a time series signal contains T time stamps and n sensors at each time stamp, the data file would include T lines, and each line has n real number splited by comma.  

### Paper

[Modeling Long- and Short-Term Temporal Patterns with Deep Neural Networks](https://arxiv.org/abs/1703.07015)


### Electricity consumption


The raw dataset is in https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014. It is the electricity consumption in kWh was recorded every 15 minutes from 2011 to 2014. Because the some dimensions are equal to 0. So we eliminate the records in 2011. Final we get data contains electircity consumption of 321 clients from 2012 to 2014. And we converted the data to reflect hourly consumption.

### Traffic Usage

The raw data is in http://pems.dot.ca.gov. The data in this repo is a collection of 48 months (2015-2016) hourly data from the California Department of Transportation. The data describes the road occupancy rates (between 0 and 1) measured by different sensors on San Francisco Bay area freeways.

### Solar Energy

The raw data is in http://www.nrel.gov/grid/solar-power-data.html : It contains the solar power production records in the year of 2006, which is sampled every 10 minutes from 137 PV plants in Alabama State. 

### Exchange Rate

the collection of the daily exchange rates of eight foreign countries including Australia, British, Canada, Switzerland, China, Japan, New Zealand and Singapore ranging from 1990 to 2016.
