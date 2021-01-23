## Functionality
Our group was able to accomplish most of what we intended to for this milestone. Starting with the control panel on the left hand side, the Statistic of Interest functionality works well and updates all three plots (map, bar plot and line plot) according to what is selected by the user. Features 2 and 3 in the control panel allow filters based on Region and Sub Region and updates all three plots accordingly. Income Group can also be used to further filter the data. Currently, the 5th feature, the Population Size slider, is not yet linked to our plots - we aim to implement this in the next milestone. The Year filter does work and updates the the line plot to only include years within the user selected range and updates the map to show the most recent year's data from the select range. Lastly in terms of control functionality, the 7th feature (Show me), allows the user to select either the top 5 or bottom 5 countries in the bottom two plots to take a closer look at the data.

All three plots have interactivity tootips which display the country as well as the value of the statistic of interest when hovering over the plots. Furthermore, zooming in on the line plot is possible and automatically updates the axis scales to accomodate the selection.
## Improvements
In order to link our Gapminder data to the Map plot, we had to first merge the country ID's provided by Joel from lecture. However, some of the names are not exact matches and thus several countries do not currently have data on the map; we aim to take a closer look and match the strings exactly for the next milestone. 

Visually, we also have a lot that can be improved upon. First, we would like to make the legend for the bar and line plots consistent with both country name order and color. Second, removing the border around the Map plot as well as choosing a better color theme that emphasizes the more extreme values. The axis titles and labels all need to be larger and more readable. Lastly, we would like to improve the overall layout to ensure it works better on different screen sizes without having to be adjusted significantly by the user.