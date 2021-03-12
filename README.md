# Kickstarting with Excel

## Overview of Project

### Purpose
The project was completed using a Kickstarter campaign dataset to analyze fundraising data related to theater and plays. The data was analyized to determine how similar campaigns fared in relation to their launch dates and fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Analysis based on launch date was completed in excel by breaking down all Kickstarter campaign data with a parent category of "Theater" and determining the number of campaigns that were successful, failed or canceled. A "year' column was created so this data could be presented for all years by month, with each month showing the number of successfull, failed or canceled campaigns. A pivot table and line chart were created to display the data.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/80215894/110994740-40528a80-8347-11eb-86db-002850162a92.png)

### Analysis of Outcomes Based on Goals
Outcomes based on goals was completed by creating a new table that broke down the fundraising goal data into smaller categories. This data was obtained by using the COUNTIF formula based on goal amount, sub-category of "plays" and outcomes. Once the numbers of campaigns for each goal amount were calculated, the SUM function was used to calculate the number of campaigns for each category of goal amount. Using the total number of projects in each goal category, the value was divided by the number of successful, failed and canceled campaigns to determine the percentage of each by goal amount. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/80215894/110994746-43e61180-8347-11eb-8e23-c6f24ad7bfe5.png)

### Challenges and Difficulties Encountered
Extracting the dates of the campaign could have proven difficult if the format of the launch date had been in a text format and not a date format. I did have issues initially with the Outcomes Based on Goals because I created a pivot chart instead of a plain line chart so was not able to format to match the example in the challenge. I removed the pivot chart and table and was able to insert a plain line chart and was able to match the image in the challenge.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? There are two conclusions that I am able to draw by looking at the data of Outcomes Based on Lauch Date. The first is that the months of May, June and July seem to be the best months for fundraising for theaters in general. These months have success rates that are much higher than all other months. It is worthy to note that the failure rate is fairly flat and fluctuates very little over the course of all months. Second, these same months also have more fundraisers for theater than other times of the year, doubling the number of some other months.

- What can you conclude about the Outcomes based on Goals? When looking at the data from Outcomes based on Goals, the data shows that fundraising campaigns for plays are more successful when they are less than $5000.

- What are some limitations of this dataset? I think the dataset is limited a bit by geography. We do know the fundraising outcomes for countries but, in the US specifically, it would be good to know cities or even states. If I am wanting to have a fundraiser for a play in Kansas for instance, the result may be much different than if I were to have the same campaign in New York City

- What are some other possible tables and/or graphs that we could create? I would narrow the focus of the Outcomes Based on Launch Date to only Plays and not Theater in general as well as by country. This may be more meaningful data for our client or can be used to compare the overall graph with the filtered graph. I would also create a box and whisker chart showing the Outcomes Based on Goals outliers. The results are mis-leading when only viewing the line chart. For example, campaigns from $35000 to $44999 show a 67% success rate, but there were only 9 projects total, compared to 720 projects in the less than $5000 range. A box and whisker chart can show that these values are outliers.
