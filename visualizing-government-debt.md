| [home page](https://kulmeher.github.io/TSWD-Repository/) | [visualizing debt](visualizing-government-debt.md) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

[Visualizing Government Debt HTML link](https://kulmeher.github.io/TSWD-Repository/visualizing-government-debt.html)

### Visualizing Government Debt
We started with our first public assignment this week. Here, I am implementing the data visualization techniques I have learned in weeks one and two in order to recreate this OECD data on government debt 1. For this assignment, we worked with this one data set to produce three different data visualizations. The second and third visualizations were created using the free platform, Flourish.

#### First Data Visualization: Simple Bar Graph
The first data visualiation comes directly from the OECD website. [^1] This bar graph is a simple overview of the ratio of Government Debt to GDP, within a single year. For this viz, I used the year of 2019. 

<iframe src="https://data.oecd.org/chart/6Y2P" width="800" height="600" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</iframe>

#### Second Data Visualization: Grid of Line Graphs

For our second data visualization, we created a grid of line charts with guidance from our class instructors. This grid of lines charts depicts the ratio of Government Debt to GDP, for individual countries (each country has one line chart, the grid is made up of all countries for which we have data), with the line indicating the ratio of debt to GDP of that specific country, beginning in 1995, and going all the way until 2019. The color of the lines has been changed to green, a secondary color, to draw attention to each countries ratio, in a way that is eye-catching yet not overwhelming. The use of color here is intentional, as the only display of a bright color within the entire grid. The rest of the grid is black and grey, denoting background information. Finally, the x-axis is only found at the bottom of the grid, in order to not repeat information unnecessarily. As this grid has many entries, it may require some scrolling from the reader to interpret the initial graphs, but the increased white space is worth this trade-off.

<script src="https://public.flourish.studio/resources/embed.js"></script>

#### Third Data Visualization: Individual Take on Above Information
#### Dynamic Scatterplot and Line Graph in One

Finally, here is my visualization created for this data. Instead of creating multiple line charts, I chose to visualize the data as a dynamic scatterplot and line graph combined. The line graph with dot's symbolizes each countries GDP to Debt Ratio for that year. In this way, all of the information is easily interpretable. If information on a single year is needed, the user can toggle between years using the time slider. When the time slider is paused, the user can get information on the debt to GDP ratio for a single country at one year in time, and compare this information with other countries. When the time slider is played, the user can glean valuable insights on Government Debt to GDP ratios over time.

<script src="https://public.flourish.studio/resources/embed.js"></script>

I will now compare each of these data visualizations based on their use of color, and the effectiveness of the overall visualization.

1. Use of Color
   - Data Viz 1: In data viz 1, the use of color seems haphazard. Certain countries have been highlighted, but there does not seem to be any reason for the use of color, or the selection of those countries. Through the judicious application of color, this bar chart could clearly inform a reader of a certain trend or data point. Instead, the chart fails to offer a cohesive vision, or story.
   - Data Viz 2: In data viz 2, we see that the use of color is more intentional. The background of the grids utilizes white space and the colors black and grey, while the main data points (lines on the graphs), are in a shade of green. This has the effect of clearly highlighting the main point of the visualization -- ie, the lines depicting the ratio of Government Debt to GDP.
   - Data Viz 3: In data viz 3, we see that the use of color is also intentional. The background of the graph utilizes white space, and the colors black and grey. The year is depicted in grey, behind the data points -- so while it is visible, it is not occupying too much of the user's visuals. Finally, it is also implementing complementary colors of blue and orange. Blue indicates the range of the countries Debt to GDP ratio, from 1995 to 2020, while the orange dot indicates the specific ratio for the year in question.

2. Effectiveness of Visualizations
   - Data Viz 1: Here, the information is provided at a glance, for a specific year or range of years. In our example, we used the year of 2019, but on the OECD website, you are able to adjust this time period 2 [^2]. However, the confusing use of color hinders clarity. This graph would be most useful for the purpose of comparing the debt to GDP ratio of countries at a glance, for a specific time period.
   - Data Viz 2: In data viz 2, we see that the information at a glance is the ratio of debt to GDP for specific countries over a time period (1995-2019). It is not easily apparent what the ratio is for a given year. A country by country comparison can take place, but over the longer term time period. Additionally, due to the large quantity of line graphs within the grid, it is not easy to compare countries that are not placed close to one another.
   - Data Viz 3: In data viz 3, we see that both the information from data viz 1 and data viz 2 are visible at a glance -- we can compare the debt to gdp ratio of countries over a long time period, or a single year period, and we can see at a glance, what the individual ratio of debt to gdp for countries has been over time. This data visualization falls short in that it is dynamic -- due to the use of the time slider, a reader may need to spend more time on the graph to toggle between the different years. However, this time slider has the benefit of helping the information be conveyed in a clean way -- thereby increasing total clarity.

Overall, due to the use of color, and effectiveness of the visualizations, elaborated on above, I prefer data viz 3 to data viz 1 or 2.

[^1] The source for this data is at the following link. [OECD Data on Government Debt] (https://data.oecd.org/gga/general-government-debt.htm) 
[^2] Ibid. 
