# Understanding Violence: Visualizing the Who, What, When, Where, and Why of Hate Crimes
Echo Nattinger

## What is your current goal? Has it changed since the proposal?
My goal has remained the same since the proposal: providing visualizations that highlight information about the perpetrators and victims of hate crimes. I hope my combination of different types of visualizations allow viewers to better understand, and thus prevent, targeted violence. 
Since the proposal, I have focused less on the idea of using supplementary polling data. I have not abandoned this idea completely, but it is not my priority at this time.

## Are there data challenges you are facing? Are you currently depending on mock data?
I am using real data from the FBI. There are some quirks of the data that have proved difficult:
1) "Crime bias" is recorded in an extremely granular way (over 300 distinct categories) that means doing aggregations with bias requires some pre-processing. My current plan is to focus only on the most "popular" biases, but I have considered ways to aggregate different categories together with some string parsing (I briefly discussed this with Prof. Turk in OH).
2) The same issue as (1) exists with other categorical variables such as incident Location. I have taken the same approach so far.
3) There are few quantitative variables in this dataset -- all relate to the number of victims and offenders in a given incident. I've built a scatterplot with these columns, but other than that my comparisons will be between categorical variables.

## Describe each of the provided images with 2-3 sentences to give the context and how it relates to your goal.
### Image 1
![visualization](https://github.com/user-attachments/assets/5757a4aa-e75c-4344-bd3e-e77e3c84ffbf)

This simple line chart demonstrates the prevalence of hate crimes over time -- specifically from 1991-2023. We see a particular surge in 2001, as well as a steady increase since 2018. I hope to use this chart in the final narrative as a simple way to understand the changing rate of hate crimes over time.

### Image 2
![image](https://github.com/user-attachments/assets/c3081964-f08e-42ad-956d-f23f891e93a5)

This line graph demonstrates the prevalence of hate crimes over time, but broken down the "bias" of the crime. We can see that Anti-Black crimes are the most prevalent type of hate-crime every year, while Anti-Jewish hate crimes have streadily risen since 2021. I hope to use this graph to demonstrate how hate crimes affect different populations at different rates, and how those rates change over time.
Note: There are over 300 types of bias represented in this dataset. For this graph, only the ten biases with the highest hate crime rate were depicted.

### Image 3
![visualization3](https://github.com/user-attachments/assets/da8088c1-62c0-4030-a62f-22392a0646a5)

This heatmap demonstrates the seasonality of hate crimes by showing the days and months in which hate crimes surge. We see here, across the 30+ years represented in this dataset, hate crimes are concentrated in the middle of September/end of October, and are less frequent in December. I hope to use this graph in my final narrative to show when hate crimes are most likely to occur.

### Image 4
![image](https://github.com/user-attachments/assets/8471a5c7-9b49-43d5-a2ae-7faedcc667c3)

This chloropleth map illustrates the prevalence of hate crimes across the United States, coloring each state by its total number of hate crime incidents from 1991-2023. We see California has by far the highest rate of hate crimes, with New York/New Jersey also showing higher rates. I hope to use this map to demonstrate not only where hate crimes occur, but address and possibly dispel stereotypes about hate crimes being concentrated in "conservative" areas of the country.

### Image 5
![image](https://github.com/user-attachments/assets/283e4797-7fa8-4631-91bf-4c6c094e1fbb)

This bar chart demonstrates the amount of total hate crime incidents grouped by offender race. We see that most hate crimes are committed by white individuals, but there is a lot of missing data ("Unknown" offender race). I want to use this graph to complement the previous chart that shows the most prevalent biases -- we can compare characteristics about the perpetrators vs. victims of hate crimes. 

### Image 6
![image](https://github.com/user-attachments/assets/f18b4248-c39b-4c1e-a063-40cdd34d3f00)

I view this graph as central to my narrative -- demonstrating how large-scale political events lead to an increase in targeted violence. This graph shows occurences of hate crimes throughout the past 5 years, focusing on the most prevalent biases in that timeframe. I've annotated the graph to mark notable sociopolitical events that may help explain sudden increases in hate crimes against certain groups.

### Image 7
![image](https://github.com/user-attachments/assets/0a3eec0e-e3c0-40ba-ad64-570277dc517d)

This scatterplot focuses on the strange relationship between total offenders vs. total victims in hate crimes. Among crimes with at least 1 individual victim (i.e., not just property crime), most incidents appear to have less than 10 total offenders and less than 20 total victims. However, the events with the highest number of individual victims (above 60) appear to be largely perpetrated by individual offenders. Conversely, the hate crimes perpetrated by large groups (50+ offenders) appear to have fewer than average victims. I hope to use this graph in my final narrative to provide insight on "who" is perpetrating hate crimes -- individuals vs. large collected groups.

### Image 8
![image](https://github.com/user-attachments/assets/931c9ec4-e34c-4779-9895-f81df503655d)

Similar to the previous bar chart, this chart demonstrates the most common locations at which hate crimes occur. Far and away the most popular is personal residency, followed by roads and highways. While there are many cases of unknown location, I hope to use this graph to further focus on the "where" of hate crimes.

## What form do you envision your final deliverable taking? (An article incorporating the images? A poster? An infographic?)
I envision developing a report that spans several pages, including all of the visual graphics alongside commentary.
