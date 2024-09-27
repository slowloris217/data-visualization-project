# data-visualization-project

This project will delve into Beijing's air quality.

Using the data obtained from multiple air quality stations located around Beijing,
we are able to analyse the 6 main air pollutants.

Summary of analysis:

Plotting the average PM2.5 and PM10 pollutants over the 4 years, we notice a clear a trend between the two.
When one goes up in concentration, so does the other. There may be a correlation here.

Seeing that the highest monthly average for PM10 was in the 150 ug/m^3 range, while the highest recorded concentration was 999 ug/m^3,
I assumed this was an outlier.
With the use of a boxplot I was able to confirm this.

Observing the average O3 levels depending on the time of day, we notice levels start to rise at around 9am, peaking at 4pm.

The carbon monoxide levels seemed to follow a "U" shaped pattern each year. It would reach it's half way through the year and peaking during the end of the year.

Using Breeze Technologies air quality index, a air quality rating was assigned to each row of data.
Observing the plot, Beijings air quality seems to contain higher levels of pollutants then desired a large portion of the time.


## Sources:
---

-Chen,Song. (2019). Beijing Multi-Site Air Quality. UCI Machine Learning Repository. https://doi.org/10.24432/C5RK5G.

-Heinecke, R. (2024) How we calculate our air quality index and why we need it, Breeze Technologies. Available at: https://www.breeze-technologies.de/blog/what-is-an-air-quality-index-how-is-it-calculated/ (Accessed: 25 June 2024). 
