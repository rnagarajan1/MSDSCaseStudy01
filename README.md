#Case Study 01 <br />
author: "Rangaswamy Nagarajan" <br />
date: "June 30, 2017"<br /> 

This is a Case Study created for MSDS 6306 course based on Beers.csv and Breweries.csv data provided.

#Data Set Info <br />

Two data sets are available for analysis. Beers and Breweries

Breweries dataset contains the list of all the breweries by City and Statewise in the USA.
It also contains the Name of the brewery and an ID for the brewery.

Beers dataset contains a list of beers available in USA.
The details that are avaialble in the dataset are Name, Beer ID, Brewery ID, Alcohol by Volume(ABV), International Bitterness Unit(IBU), Style and Ounces.
Based on the Brewery ID information we can tie the data back to the Brewery data and identify where a particular Beer was brewed.

A manually created StateNames.csv is also included as a dataset to represent state names instead of the codes in the output. The dataset has 51 US state codes and names. This data is merged with the Brewery data based on the State_code data in StateNames.csv file and State in Breweries.csv file.

####Common glossary terms used for the data sets. <br />
####Beers.csv: <br />
Name: Name of the beer. <br />
Beer ID: Unique identifier of the beer. <br />
ABV: Alcohol by volume of the beer. <br />
IBU: International Bitterness Units of the beer. <br />
Brewery ID: Brewery id associated with the beer. <br />
Style: Style of the beer. <br />
Ounces: Ounces of beer.

####Breweries.csv: <br />
Brew ID: Unique identifier of the brewery. <br />
Name: Name of the brewery. <br />
City: City where the brewery is located. <br />
State: State where the brewery is located.

####StateNames.csv: <br />
State_Code : Two letter code for the state. <br />
State_Name : State name.

#Related links and Prerequisites
  * <a href = "https://cran.r-project.org/bin/windows/base/R-3.4.0-win.exe">R version 3.4.0</a>
  * Nice to have <a href="https://git-scm.com/download/win">Git </a> and <a href = "https://github.com/">GitHub Account</a>

#Goal
  * To Create an RStudio project for the analysis of the data sets include the following.
	* A README file in the project root directory that includes an explanation of the purpose of the project and the other files
	* A data directory containing files to load in and clean up the data. 
	* An Analysis directory containing a file (or files) for exploratory data analysis on the clean data to visualize the relationship between ABV and IBU.

#Deliverable 
  <a href="https://github.com/rnagarajan1/MSDSCaseStudy01">CaseStudy01</a>
  
#Author
 See the list of <a href ="https://github.com/rnagarajan1/MSDSCaseStudy01/graphs/contributors">Contributors</a> who contributed for this project.
