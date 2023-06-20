Project Title:
Crime in Chicago for years 2018-2022

Team 3 members:
Aileen Alvaraz
Alicia Hlavac
David Kauffman
Jason Pealy
Ralf Welvers

The code can be found in the following file in the main branch:
team3_chicago_crime.ipynb

The slide deck can be found in the following file in the main branch:
Team 3 Chicago Crime Insights.pdf

The complete writeup is below.

As current and former residents of Chicago our core interest was to better understand the state of crime in our city. News media typically report on those crimes that grab the most attention; namely homicides. We set out to determine what is really happening.

We began our analysis at a high level and with each question we went deeper in the data. As it turns out, theft crimes are the number one crime type in Chicago at 41.7% of all crime. Homicides, on the other hand, represent only 0.3% of all crime.

Another interesting insight is the location of crimes. We initially thought that most crime occurred on the south side. Turns out district 11 has the highest instance of crime. District 11 is just west of downtown.

To help us understand whether or not different districts of Chicago experience differing amounts and rates of crime we conducted two chi-squared tests. The first null hypothesis was that all areas of Chicago experience the same amount of crime. The results of this first test revealed that we can reject the null hypothesis. The first null hypothesis was that all areas of Chicago experience the same rate of crime. The results of this second test revealed that we cannot reject the null hypothesis. This is because the rates are so close together statistically.

When we look at whether different areas of Chicago are more prone to crime than others, we can see that there are differences between districts.  We examined the number of crimes committed over a five year period from 2018 to 2022, and looked at the total crimes committed, the total population, and the per capita crime rate per 1,000 people living in Chicago. Then, we split Chicago down into its police districts to see if there is any difference between the number of crimes committed and the location in Chicago that is looked at.
	
To begin, we assessed the percentage of crimes per district relative to the total crimes committed across all districts during the five-year period. District 11 exhibited the highest percentage at 6.807%, while District 20 had the lowest percentage at 1.913%. Additionally, we examined the percentage of each district's population in proportion to the total population. District 19 had the highest percentage at 7.509%, whereas District 1 had the lowest at 2.192%.By graphing these percentages, we gained a visual representation of each district's crime and population proportions compared to other districts. Notably, districts 25, 10, 19, 5, 14, 16, 17, and 20 showed higher population percentages relative to the total population than crime percentages relative to total crime. These districts should be examined when we look at per capita crime data, because these districts may have a lower per capita crime rate because of their high population percentage and lower crime percentage. 

We then turn our analysis to the crime rate per capita per 1,000 residents of Chicago.  When we look at these specific districts (25, 17, 16, 9, 14, 19, 25, 10, and 5), we can conclude that district 20 had the lowest per capita crime rate per 1,000 people at 19.07.  District 10 was the 8th lowest at 30.58, while district 19 was 6th at 25.46.  District 5 had the 9th lowest per capita crime rate per 1,000 people at 36.99, district 14 was 5th at 25.08, district 16 was 3rd at 24.04, and district 17 was 2nd at 21.61.  All of the districts above make up the lowest per capita rates per 1,000 people by district. Therefore, the data suggests that using the percentages of populations as a percentage of total population along with their percentages of crime as a percentage of total crime was a good indication as to per capita crime rate (although no definite correlations can be drawn from this data).  This makes sense, as the per capita crime rate looks at the number of crimes per unit of population, so as population increases and crime decreases, we would expect the per capita crime rate to decrease.  By this data, it would suggest that different districts and locations in Chicago have a different makeup of total crime percentage, and thus are more prone to crimes than others.
![PerCapitaCrimeRatebyDistrictper1000People](https://github.com/ralfwelvers/project1_chicago_crime/assets/127240852/09ebe7c3-c65c-480b-a65b-98cd0a686c3a)

Next, we examined the per capita crime rate per 1,000 residents in each district. District 1 has the highest rate at 97.49, while district 20 had the lowest at 19.07.  This is a numerical difference of 78.42 crimes per 1,000 people and a 134.55% difference.  We can also observe that the mean of all of the districts’ per capita crime rate per 1,000 people is 46.75, which lies between district 22 and 15 on the graph above.  The median is 44.40 reported crimes over the five year period per 1,000 residents.  We should note that our mean is close to our median, suggesting that our data may not be very skewed and that the mean is the average crime rate across all districts.  Thus, we can conclude districts 22, 8, 12, 5, 10, 25, 19, 14, 9, 16, 17, and 20 fell below the mean across all districts, while the remaining districts fell above the mean.  For example, district 20 had an average per capita crime rate per 1,000 that was 27.68 below the mean across all districts.  This is one way we can look at the differences between districts; we can  tell whether they are higher or lower compared to how other districts compare with the mean.  The table below summarizes the difference between the per capita crime rate per 1,000 people and the mean.  We can see that districts varied between each other when these differences were taken, suggesting that the location in Chicago does matter in relation to crime rates. We should note, however, that there are limitations while looking at the mean.  For example, some of our larger districts with higher crime rates can affect the mean’s overall measure.  
![SummaryTable](https://github.com/ralfwelvers/project1_chicago_crime/assets/127240852/11be4f62-667a-42fb-a22c-d1c14f1127e7)

We took a look at the total number of crimes committed in each district over the five year period, and visualized them on a map.  As the number of total crimes increases, the marker on the map becomes a darker shade of blue.  District 1, 12, and 18, all located near the loop, the near north, and the near south community areas in Chicago, all have a total crime count between 59,665 and 61,019 crimes over the period from 2018-2022. These are high counts, however, they aren’t the highest counts observed.  Directly west of these districts is district 11, which has a total crime count of 77,986.  This was the highest crime count we have observed.  As we continue to go farther south, just north of the I-294/I-57 interchange, we see the number of crimes reach a maximum at 74,703 for district 6. This is the highest number of crimes per district.  District 8, which is on the southwest side of Chicago, has a total crime count of 67,499 crimes. District 20, north of the Loop, had the least amount of crime incidents at 21,917 crimes.  In conclusion, we can see that crime numbers per district do change district by district, and certain areas of Chicago have more prevalent crimes than others.  

Overall crime numbers declined year over year from 2018-2021, but increased in 2022. The largest decrease was between 2019 and 2020, at 19.74%. The only increase was between 2021 and 2022, at 14.97%. Despite this increase in the final year, overall crime in 2022 was still 11.63% lower than in 2018.

The proportions of crime remained fairly steady over the observed time frame. The most notable difference is that as overall crime decreased, the rate of Assault and Battery as a proportion of crime increased, from 26.8% to 30.2%. The inverse is true for thefts of all types, which declined from 42.8% to 39.2%.

Most categories of crime saw declines from 2018 to 2022 that were similar to the decline of total crimes, but there were some significant differences. Drug related crimes had by far the largest decline at 68.98%. On the other hand, arson (11.96%), homicide (19.73%), and weapons related crimes (58.56%) saw significant increases. Sexual related crimes didn’t follow a particular pattern compared to the rest of the data, but were about the same in 2022 as in 2018 (up 0.50%)
![Sexual Crimes and Crimes Involving Children per Year](https://github.com/ralfwelvers/project1_chicago_crime/assets/127240852/3e6ad888-ae24-4fbf-9045-b1c919069254)

Rates of heinous crime committed were relatively low in Chicago during this period in absolute terms, as well as on the basis of percentage of crimes committed, and on the number of occurrences per 1k people in the population.
![heinous_pie](https://github.com/ralfwelvers/project1_chicago_crime/assets/127240852/c31a2848-60a4-4671-9642-ef19716bb618)

The number of reported instances of Arson saw a noticeable uptick from 2019 to 2020 before dropping off sharply in 2021 and again in 2022.  Homicides similarly saw a large increase in occurrences from 2019 to 2020 but - unlike Arson - continued to rise through 2021 before dropping off sharply from 2021 to 2022 (albeit still at a significantly higher level than in 2019).  The number of reported kidnappings fell in each year except from 2021 to 2022 where they rose back to 2020 levels.
![heinous_percent (1)](https://github.com/ralfwelvers/project1_chicago_crime/assets/127240852/11779dbc-ab58-4d10-a289-a0de13b83e77)

Overall levels of reported crime actually fell in each subsequent year during the data sample except in the final year (2022).  As a percentage of crimes committed, heinous crimes increased in the first two periods (2018 to 2019 and 2019 to 2020) before falling from 2020 onwards.
![typecounts_df_all](https://github.com/ralfwelvers/project1_chicago_crime/assets/127240852/7081987e-e14d-4041-93bf-76f11166d7a5)
![type_percent_df_all](https://github.com/ralfwelvers/project1_chicago_crime/assets/127240852/6baff183-5ed7-409a-8145-20b087a6f1b0)

Ultimately, theft is the predominant crime with 41.7% of the mix. District 11 has the highest number of total crimes. District 1 has the highest crime per capita. The total number of crimes fell from 2018 to 2021, but rose in 2022. Arson and homicide saw a notable uptick from 2019 to 2020 (both in absolute terms and on a relative basis).  Homicides continued to rise into 2021.  Both leveled off and started to fall again after 2021.  Despite large percentage increases during the pandemic period, both categories remain very small as a percentage of overall crimes committed. Kidnappings saw a significant fall during the observation period.  This began before the onset of the pandemic.





