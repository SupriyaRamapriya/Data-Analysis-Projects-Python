# Data-Science-Projects-Python
The following repository consists of Data Science projects / analysis using Python . 

# Min. Max. Temp. Analysis:
The following analysis aims at giving a clear picture of the temperature changes in given region of observation. The visual leverages the guidelines of effective visual design
and follows Cairo's principles of visual analysis. 

## STEPS FOLLOWED:
1) Required libraries for analysis are loaded in Jupyter notebook
2) The data in .csv format is read to a specified Dataframe using Pandas library present in Python
3) All dates are converted to DateTime format and Dates are converted to Day_of_the_Year
4) Dataset is considerably cleaned to suffice easy analysis without loosing any important data
5) Maximum and Minimum tempearaures are seperated out and mean is calculated using Numpy library present in Python
6) All the required subsets of original dataset is merged using Pandas to help plotting
7) Visual of Maximum and Minimum temperaures are plotted using "matplotlib" library present in Python

## CONCLUSION:
From the visual we can see that on an average the maximum and minimum temperatues run a difference of 10degCelsius throughout the year. We can also see a huge temperature variation on some days in the year 2015 as compared to all the years from 2005. This visual might be helpful for further climate change study and we can use the same to draw many insightfull conclusions.
![2021-10-25](https://user-images.githubusercontent.com/31743520/138808022-a49dadd6-4c59-4e41-addf-af7bcde9bd83.png)




# Urban_UnemploymentRate_India:
The dataset used for the visualization is obtained from CMIE website. CMIE stands for Centre for Monitoring Indian Economy which conducts weekly and monthly surveys over 160,000+ households. I have taken a period from January 2020 to August 2021 since during this time India was recovering from first wave of COVID and was about to enter second wave. Economy and employment both were hit and above visualization helps to know about this trend in a graphical manner and gives a clear picture.

For the above visualization , mean of Unemployment Rate is calculated over every month throughout the specified period. We can see that Union Territories are worst affected in the months of April and May. The spike goes up to 46% from the lowest being 6% in Union Territories. From this trend we can further have a research as to why during those months the unemployment rate is high and help the local people to reduce the same.

## Cairo's Principles:
1) Truthfulness : The data is presented as is and is not manipulated.
2) Beauty : More emphasis is given to the representation and clear markings rather than beautifying the visual. The color palette used is disable friendly.
4) Functionality : Direct labelling is done and one glance through the graph will be enough to get down with the results.
5) Insightfulness : The visual representation leads the reader for new learnings and can definitely be used for future research works.

![2021-10-25 (1)](https://user-images.githubusercontent.com/31743520/138808276-9afe8635-1fa5-4ec3-b5ff-4d2ce1d16d45.png)


# Olympic_Medal_Trend:

The analysis aims at giving a clear picture of how many Gold , Silver and Bronze medals are won altogether by each country. Here I have chosen India and United States for analysis from the year 1980 till 2020 . Comparison of bith countries is also donw using subplots. 

## STEPS FOLLOWED:
1) The dataset is derived from wikipedia page for each year Summer Olympics from 1980 for all the countries.
2) The dataset is cleaned with the help of "regex"
3) The required countries are then selected and dataset is manipulated to help for analysis without compromising or losing any original data
4) Suitable rows are added to help plotting
5) Stacked bar plot is abtained for both countries with the number of medals won every year in Summer Olympics
6) Subplot for comparison is obtained at the last

## CONCLUSION:
From the visual we can see that there is an increasing trend in obtaining medals for India , whereas United States medal count has always been on a average from 100-120 medals each year. This study can be further used for predicting outcome in next Summer Olympics.  

![2021-10-25 (2)](https://user-images.githubusercontent.com/31743520/138808398-1fe66969-12af-444c-afac-638d7f6da42e.png)

