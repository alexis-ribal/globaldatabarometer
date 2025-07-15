# Country benchmarking tool of the Global Data Barometer 2nd Edition data

The Global Data Barometer (GDB) is a comprehensive database that assesses foundational elements of data systems, specifically focusing on Data Governance Foundations and Critical Competencies. These aspects examine the legal, institutional, and human capacities essential for developing effective and responsible data systems. For a detailed understanding of its methodology, please visit the [publication page](https://globaldatabarometer.org/) to read more about its methodology.  

Recognizing that robust governance is a fundamental prerequisite for leveraging data as a public good, this dashboard integrates data from the World Bank's Worldwide Governance Indicators (WGI). This allows for the identification of patterns between strong governance dimensions and improved data accessibility.

This interactive data visualization tool is designed to benchmark country-specific GDB cluster scores against both overall averages and selected comparator countries. The dashboard features a single control panel that dynamically updates four distinct charts, each providing a unique perspective on the data. A description of each panel and guidance on interpreting its corresponding figure is provided below.

## Instructions:

1. Open the live dashboard app here [https://alexis-ribal.github.io/globaldatabarometer/](https://alexis-ribal.github.io/globaldatabarometer/)
2. Select a country of interest.
3. Select a comparator country.
4. Select one thematic cluster from the Global Data Barometer.
5. Select one dimension from the Worldwide Governance Indicators.

## Panel A. How does the selected country score against overall scores?
This horizontal bar chart illustrates how the selected country's scores for each Global Data Barometer (GDB) cluster deviate from the overall average scores of the sample. Bars in green indicate clusters where the selected country performed better than the average, while bars in red represent clusters where it performed worse. The length of each bar signifies the magnitude of the deviation, measured in score points. A country with a greater number of green bars demonstrates stronger overall performance relative to the sample average.

## Panel B. How does country A compare with country B?
This scatterplot directly compares the GDB cluster scores of Country A (on the x-axis) against those of Country B (on the y-axis). A 45-degree dashed line serves as a reference point. Clusters appearing below this line (in green) indicate areas where Country A has a better score than Country B. Conversely, clusters appearing above the line (in red) signify areas where Country B performed better. Therefore, a prevalence of green points suggests that Country A generally scores higher across the GDB clusters compared to Country B.

## Panel C. How does the selected country score in GDB?
This density plot visualizes the distribution of scores for the Global Data Barometer cluster chosen in the "Dashboard Controls" across all 43 countries in the sample. The vertical dashed line highlights the selected country's score for that specific cluster. If this line is positioned to the left of the distribution's peak, it suggests that a majority of countries in the sample performed better than the selected country in that cluster. If the vertical line is to the right of the peak, it indicates that the selected country is performing better than most other countries in that specific cluster.

## Panel D. How does the score of the selected country compare with WGI scores?
This scatterplot presents a comparison between the score of the selected Global Data Barometer cluster and the score of the selected Worldwide Governance Indicator (WGI). The selected country is prominently highlighted in red for easy identification. An upward trend among all points in the scatterplot suggests a strong correlation between the two indicators. If the selected country's point is located in the top right quadrant of the scatterplot, it signifies strong performance in both data governance (GDB) and overall governance (WGI). Conversely, if the country's point is in the bottom left quadrant, it indicates weaker performance across both indicators.

## Sources:
[The Global Data Barometer 2nd Edition](https://globaldatabarometer.org/)
[Worldwide Governance Indicators, 2024 Update, World Bank](https://www.worldbank.org/en/publication/worldwide-governance-indicators)


Author: [Alexis Rivera-Ballesteros](https://alexis-ribal.github.io/)
Contact: alexis[at]epsilonmas.com

License: CC-BY

