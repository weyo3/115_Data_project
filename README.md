# 115_Data_project

## Washington Emissions Data

## Motivation

Health is a huge concern to everyone, or it should be. Our health is affected by the foods we eat and the environment we live in. Nowadays there is air quality control systems where it simply states how good or bad the air quality is at your location. The PMEL Carbon Group of Seattle Washington conducted [research](https://www.pmel.noaa.gov/co2/story/WA+State+Emissions) in 2002 that shows emissions from different sources. Those are: commercial, industrial, residential, electric production, and mobile (cars and other type of vehicles). I wanted to take a further look into the specific biproducts that companies produced. The question I am trying to investigate is whether the emissions products from these companies are strictly correlated with each other or are they dependent on the type of company. 

## Figure 1

<img src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Hwk11_1a.png">
caption: Figure 1 shows the first two principle components that explain 73% of the variance of the Washington State emsissions data set. It includes categories of CAP major, HAP major, both, non-major, synthetic non-major and unknown. 


*Note:* CAP major is the limit of pollution. HAP major are hazardous air pollutants. 

## Data Sources
I obtained the data from the [Washington State Ecology](https://ecology.wa.gov/Research-Data?type=2&topics=&cats=&searchtext=Washington+Reported+Point+Source+Emissions+(2009+%e2%80%93+2019)&searchmode=allwords) website, the [here](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fecology.wa.gov%2FDOE%2Ffiles%2F89%2F89e90a3e-6454-4b63-98a6-490dd916773d.xlsx&wdOrigin=BROWSELINK) is the link to the document. The data included emissions data from 2009 to 2019, that included particle matter 10 (PM), PM 2.5, sulfur dioxide (SO2), nitrogen oxide (NOx), volatile organic compounds (VOCs), carbon monoxide (CO), and ammonia (NH3). The companies are also categorized in criteria air pollutants (CAP), hazardous air pollutants (HAP) major, HAP & CAP major, non-major, synthetic non-major, and unknown.  There are 407 companies from 29 counties in Washington state that are reported in this data set.
