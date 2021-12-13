# 115_Data_project

## Washington Emissions Data

## Motivation

Health is a huge concern to everyone, or it should be. Our health is affected by the foods we eat and the environment we live in. Nowadays there is air quality control systems where it simply states how good or bad the air quality is at your location. The PMEL Carbon Group of Seattle Washington conducted [research](https://www.pmel.noaa.gov/co2/story/WA+State+Emissions) in 2002 that shows emissions from different sources. Those are: commercial, industrial, residential, electric production, and mobile (cars and other type of vehicles). I wanted to take a further look into the specific biproducts that companies produced. The question I am trying to investigate is whether the emissions products from these companies are strictly correlated with each other. 

## Figure 1

<img src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Hwk11_1a.png">
caption: Figure 1 shows the first two principle components that explain 73% of the variance of the Washington State emsissions data set. It includes categories of CAP major, HAP major, both, non-major, synthetic non-major and unknown. 


*Note:* CAP major is the limit of pollution. HAP major are hazardous air pollutants. 

## Data Sources
I obtained the data from the [Washington State Ecology](https://ecology.wa.gov/Research-Data?type=2&topics=&cats=&searchtext=Washington+Reported+Point+Source+Emissions+(2009+%e2%80%93+2019)&searchmode=allwords) website. The data included emissions data from 2009 to 2019, that included particle matter 10 (PM), PM 2.5, sulfur dioxide (SO2), nitrogen oxide (NOx), volatile organic compounds (VOCs), carbon monoxide (CO), and ammonia (NH3). The companies are also categorized in criteria air pollutants (CAP), hazardous air pollutants (HAP) major, HAP & CAP major, non-major, synthetic non-major, and unknown.  There are 407 companies from 29 counties in Washington state that are reported in this data set.

## Data Processing

The main issue for this data set is that it has a large amount of missing data. The missing data is from multiple columns: PM10, PM2.5, SO2, VOCs, CO, and NH3 columns. To correct this, I used the is.na() function to find all of missing data in these columns. After identifying these cells, then I used the na.omit() function that omits the rows with missing data in these columns. Finally, there remained 731 observations, and 145 companies throughout 19 counties in Washington state.

## Visualization 
 
I created histograms for each of the emission products showing the range of output from 2009 to 2019. Companies are only allowed to pollute at certain levels based on their emissions permit. However, companies are allowed to buy, sell, and trade emissions permits. Thus, we see some values on the far right. The histograms unsurprisingly are skewed towards the left of the distribution. This is because we know that companies will stay close to how much their permits allow them, in this case, most emissions are less than 50,000 tons of pollution from companies reported in this data set. 

# <image src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Figures/PM10.png"> <image src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Figures/PM2.5.png"> <image src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Figures/SO2.png"><image src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Figures/NOX.png"> <image src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Figures/VOC.png"><image src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Figures/CO.png"><image src="https://raw.githubusercontent.com/weyo3/115_Data_project/main/Figures/NH3.png">
 
