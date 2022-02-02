# Engeto_Data_Academy_Python_Project

*******************************************************
Data Analysis of Bike Sharing in Edinburgh:
*******************************************************

Project Conclusion:
---------------------
1. Picady Place, Royal Highland Show, Cycling Scotland Conference, Edinburgh University Sports Fair, Depot are 5 stations with the lowest number of visits and can be considered as inactive.

2. Portobello Kings Road, Victoria Quay, Duke Street, Leith Walk, Canonmills have highest bike surplus in the given time period from 09-2018 to 06-2021 in Edinburgh.

3. Bristo Square, St. Andrews Square, Charlotte Square, City Chambers, Pollock Halls have highest bike shortage in an given time period from 09-2018 to 06-2021 in Edinburgh.

4. Meadows East, Portobello Kings Road, Victoria Quay, Meadow Place, Canonmills are the busiest stations for bike sharing in Edinburgh.

5. Very short bike rides of duration of approximately 10-15 minutes are the most common. 
   Bike rental for more than one day occured only ones in the data set and was identified as clear outlying value.

6. The most common air distance between stations is 0.5 - 1.5 km for a single ride.

7. Air distance between stations in 2020 was longest during spring and summer season. 
   Average montly distance between stations for a bike ride was 2.0-2.5 km.

8. The highest increase of bike rides occured between April and May, 2020. 
   Total montly count of rentals is in May more than 2 times higher than in April 2020.

9. The season from May 2020 to October 2020 shows largest monthly number of bike rentals.

10. Demand oscillation seen on the time history correlates well with conclusion point nr. 9.

11. Weekend bike rides make up about half of the total bike rental per week.

12. 60% of rentals occurs on weekdays and 93% of rentals happens on days with the summed amount of rainfall below 5mm. 
    It also seems that people are more motivated to rent a bike on the weekdays despite heavy rain. 
    Daily average amount of bike rentals is largest on weekends and is achieving almost 1200 bike rentals per day, 
    when the rainfall is almost zero. 
     Statistics was prepared for the time period with highest demand for bike sharing from 05-2020 to 09-2020.

13. Strongest correlation between the number of bike rentals and weather was identified for temperature and cloud percentage parameter, 
    but the correlation coefficient indicates a moderate correlation (around +/- 0.5). 
    Correlation with the temperature is positive, correlation with cloud percentage is negative. 
     Wind speed and rainfall are less important parameters influencing demand for bike sharing.

14. Outliers are influencing the linear correlation coefficient and may have more leverage and may change the scope of the regression line. 
    Clear reasons for them should to be find and it is recommended to think about their exclusion from data set.






















Gitbash - Jupyter Notebook to PDF file:
jupyter-nbconvert Project_Python_Edinburgh_Bikes___10.ipynb --no-input --no-prompt --to pdf