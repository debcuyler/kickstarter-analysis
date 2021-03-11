# Kickstarting with Excel

## Overview of Project

### Purpose
The project was completed using a Kickstarter campaign dataset to analyze fundraising data related to theater and plays. The data was analyized to determine how similar campaigns fared in relation to their launch dates and fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Analysis based on launch date was completed in excel by breaking down all Kickstarter campaign data with a parent category of "Theater" and determining the number of campaigns that were successful, failed or canceled. A "year' column was created so this data could be presented for all years by month, with each month showing the number of successfull, failed or canceled campaigns. A pivot table and line chart were created to display the data.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/80215894/110721308-4bd67200-81de-11eb-9e52-64d6f471f9b9.png)

### Analysis of Outcomes Based on Goals
Outcomes based on goals was completed by creating a new table that broke down the fundraising goal data into smaller categories. This data was obtained by using the COUNTIF formula based on goal amount, sub-category of "plays" and outcomes. Once the numbers of campaigns for each goal amount were calculated, I used the SUM function to calculate the number of campaigns for each category of goal amount. Using the total number of projects in each goal category, the value was divided by the number of successful, failed and canceled campaigns to determine the percentage of each by goal amount. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/80215894/110721321-52fd8000-81de-11eb-9994-ecd00cb6a49f.png)

### Challenges and Difficulties Encountered
Extracting the dates of the campaign could have proven difficult if the format of the launch date had been in a text format and not a date format. I also had some problems organizing the x-axis data of the Outcomes Based on Goal line chart, to be in the correct order but was able to move two of the goal amount categories to the correct order to make sure information was correct and understandable.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? There are two conclusions that I am able to draw by looking at the data of Outcomes Based on Lauch Date. The first is that the months of May, June and July seem to be the best months for fundraising for theaters in general. These months have success rates that are much higher than all other months. It is worthy to note that the failure rate is fairly flat and fluctuates very little over the course of all months. Second, these same months also have more fundraisers for theater than other times of the year, doubling the number of some other months.

- What can you conclude about the Outcomes based on Goals? When looking at the data from Outcomes based on Goals, the data shows that fundraising campaigns for plays are more successful when they are less than $5000.

- What are some limitations of this dataset? I think the dataset is limited a bit by geography. We do know the fundraising outcomes for countries but, in the US specifically, it would be good to know cities or even states. If I am wanting to have a fundraiser for a play in Kansas for instance, the result may be much different than if I were to have the same campaign in New York City

- What are some other possible tables and/or graphs that we could create? I would narrow the focus of the Outcomes Based on Launch Date to only Plays and not Theater in general as well as by country. This may be more meaningful data for our client or can be used to compare the overall graph with the filtered graph. I would also want to somehow show that the Outcomes Based on Goals have some goal categories looking quite successful but the number of plays is so low that the data is mis-leading. For example, campaigns from $35000 to $44999 show a 67% success rate, but there were only 9 projects total, compared to 720 projects in the less than $5000 range. We may be able to achieve this by looking at outliers or variance.What are some other possible tables and/or graphs that we could create?
