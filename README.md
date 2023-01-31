
- Web page URL: https://kulmeher.github.io/TSWD-Repository/
- This repository: https://github.com/kulmeher/TSWD-Repository/


# About me

I'm a first year student at Carnegie Mellon, pursuing a Master of Science in Public Policy and Management (MSPPM for short). I am seeking to use data and visualizations to make complicated material readily digestible. I come to this work from a background in racial and economic justice. I chose to pursue a graduate degree in order to further equity in the United States, through a combination of data driven-policy, technology, and good old fashioned hard work. 

Currently, I'm hoping to push forward an explicitly equity oriented agenda in the tech space. As new technology continues to change our daily lives, I hope for a future where we are not reactively seeking to legislate or litigate preferential outcomes, but one where we bodly push forward equitable solutions to the issues of today. I see data visualization as an important part of this mission, to communicate succintly and effectively with my peers about important issues, that too often get lost within legalese and technical jargon. I hope to use the tools I learn here to communicate dense information in a palatable way. 

We live in a world of abundance, where we could all be guaranteed life, liberty, the pursuit of happiness, AND housing, healthcare, and opportunities to prosper collectively. Through effective policy choices, we can assure this future for the next generation. To create an appetite for these policies, we need effective methods of communication. That's where learning how to tell stories with data comes in.  


# What I hope to learn
I hope to learn more than my brain and my body have the time for! But, in these short few months, I would be happy to come away with a deeper understanding of: 

1. How to develop a public portfolio chronicling my attempts at useful and practical data visualizations
2. How to use new software, like Tableau
3. Color Theory -- and its applicability to the field of public policy


# Portfolio
Hi! This is my public portfolio for Telling Stories with Data at CMU! Over the course of this semester, this is where I will be uploading all of my cool work. I hope you will want to hire me after this! 

### Examples 
My future work will be available here

### Assignments
#### Week 1: 
In Week 1, we did not have any public assignments. 

#### Week 2: [Visualizing Government Debt](https://github.com/kulmeher/TSWD-Repository/blob/d3fa40e2766aea963503fc5c6ce0a1d0f788ad45/visualizing-government-debt.md)

[Visualizing Government Debt
]([url](https://github.com/kulmeher/visualizing-government-debt.html))

We started with our first public assignment this week. Here, I am implementing the data visualization techniques I have learned in weeks one and two in order to recreate this OECD data on government debt [^1]. For this assignment, we worked with this one data set to produce three different data visualizations. The second and third visualizations were created using the free platform, [Flourish](https://flourish.studio/index.html).  

##### First Data Visualization: Simple Bar Graph

The first data visualiation comes directly from the OECD website. This bar graph is a simple overview of the ratio of Government Debt to GDP, within a single year. For this viz, I used the year of 2019. 

<iframe src="https://data.oecd.org/chart/6Y2P" width="800" height="600" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</iframe>

##### Second Data Visualization: Grid of Line Graphs 

For our second data visualization, we created a grid of line charts with guidance from our class instructors. This grid of lines charts depicts the ratio of Government Debt to GDP, for individual countries (each country has one line chart, the grid is made up of all countries for which we have data), with the line indicating the ratio of debt to GDP of that specific country, beginning in 1995, and going all the way until 2019. The color of the lines has been changed to green, a secondary color, to draw attention to each countries ratio, in a way that is eye-catching yet not overwhelming. The use of color here is intentional, as the only display of a bright color within the entire grid. The rest of the grid is black and grey, denoting background information. Finally, the x-axis is only found at the bottom of the grid, in order to not repeat information unnecessarily. As this grid has many entries, it may require some scrolling from the reader to interpret the initial graphs, but the increased white space is worth this trade-off. 

<div class="flourish-embed flourish-chart" data-src="visualisation/12596184"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

##### Third Data Visualization: Individual Take on Above Information
##### Dynamic Scatterplot and Line Graph in One

Finally, here is my visualization created for this data. Instead of creating multiple line charts, I chose to visualize the data as a dynamic scatterplot and line graph combined. The line graph with dot's symbolizes each countries GDP to Debt Ratio for that year. In this way, all of the information is easily interpretable. If information on a single year is needed, the user can toggle between years using the time slider. When the time slider is paused, the user can get information on the debt to GDP ratio for a single country at one year in time, and compare this information with other countries. When the time slider is played, the user can glean valuable insights on Government Debt to GDP ratios over time.  

<div class="flourish-embed flourish-scatter" data-src="visualisation/12596419"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

I will now compare each of these data visualizations based on their use of color, and the effectiveness of the overall visualization. 

1. Use of Color
   - Data Viz 1: In data viz 1, the use of color seems haphazard. Certain countries have been highlighted, but there does not seem to be any reason for the use of color, or the selection of those countries. Through the judicious application of color, this bar chart could clearly inform a reader of a certain trend or data point. Instead, the chart fails to offer a cohesive vision, or story. 
   - Data Viz 2: In data viz 2, we see that the use of color is more intentional. The background of the grids utilizes white space and the colors black and grey, while the main data points (lines on the graphs), are in a shade of green. This has the effect of clearly highlighting the main point of the visualization -- ie, the lines depicting the ratio of Government Debt to GDP. 
   - Data Viz 3: In data viz 3, we see that the use of color is also intentional. The background of the graph utilizes white space, and the colors black and grey. The year is depicted in grey, behind the data points -- so while it is visible, it is not occupying too much of the user's visuals. Finally, it is also implementing complementary colors of blue and orange. Blue indicates the range of the countries Debt to GDP ratio, from 1995 to 2020, while the orange dot indicates the specific ratio for the year in question. 

2. Effectiveness of Visualizations
   - Data Viz 1: Here, the information is provided at a glance, for a specific year or range of years. In our example, we used the year of 2019, but on the OECD website, you are able to adjust this time period [^2]. However, the confusing use of color hinders clarity. This graph would be most useful for the purpose of comparing the debt to GDP ratio of countries at a glance, for a specific time period. 
   - Data Viz 2: In data viz 2, we see that the information at a glance is the ratio of debt to GDP for specific countries over a time period (1995-2019). It is not easily apparent what the ratio is for a given year. A country by country comparison can take place, but over the longer term time period. Additionally, due to the large quantity of line graphs within the grid, it is not easy to compare countries that are not placed close to one another.
   - Data Viz 3: In data viz 3, we see that both the information from data viz 1 and data viz 2 are visible at a glance -- we can compare the debt to gdp ratio of countries over a long time period, or a single year period, and we can see at a glance, what the individual ratio of debt to gdp for countries has been over time. This data visualization falls short in that it is dynamic -- due to the use of the time slider, a reader may need to spend more time on the graph to toggle between the different years. However, this time slider has the benefit of helping the information be conveyed in a clean way -- thereby increasing total clarity. 

Overall, due to the use of color, and effectiveness of the visualizations, elaborated on above, I prefer data viz 3 to data viz 1 or 2. 

[^1]: The source for this data is at the following link. [OECD Data on Government Debt] (https://data.oecd.org/gga/general-government-debt.htm) 
[^2]: Ibid. 


### Final Project
These placeholders will link to my completed final project soon. 
[Part I]
[Part II]
[Part III]
