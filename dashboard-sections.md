1. Geographical display of the complaint type / Descriptor dominated x zip code /Eszter makes it/
2. Compare rat sitings day to day and do machine learning predictions to predict sightings.
3. What is the average time for closing complaint and how did it change during the time?
4. What districts with more animal issues and how did it change during the time?
5. Is there a correlation or connection between places and complaints?
6. Scatter map of lon / lat to visualize complaints and incidents
7. Categorize zip codes with most common complaint
8. Forest Hills Stadium. Any animal complaints in that area (between stadium and subway).
9. add data on population size of boroughs and use it to normalize certain data visualizations such as: (divide count of complaint by population)
```
fig_agency = px.histogram(df, x='Borough', color='Complaint Type', facet_col='Agency Name')
```
