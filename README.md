# superbowl-ad-analysis-project3

By: Jessica Mroczek, Matthew Sturt, Maia Sepiashevill, and Lindsay McFadyen

Overview: 
The dataset youtube is created by FiveThirtyEight with an original source of the video data from superbowl-ads.com. The youtube.csv contains a list of 10 brands that had the most advertisements in Super Bowls from 2000 - 2020 according to superbowl-ads.com. FiveThirtyEight added the seven defining characteristics of Super Bowl ads. Numeric variables utilized were views and number of likes. The CSV had a total of 248 unique records. Following the analysis and visualization of this data, the visualizations were then added to an html local site to allow for showcasing and interacting with the data. 

Ethical Considerations:
Since the dataset includes data from YouTube, it's essential to ensure that all data used complies with the platform's terms of service and respects the privacy of content creators and viewers. This includes ensuring that any personal data is appropriately anonymized and that the use of the data does not infringe on any copyright or personal rights.

Coding approach:
As a team we approached the coding and visualization of our code in several different ways. We used HTML, CSS Stylings, PlotlyExpress, Python, Pandas, and Jupyter Notebook. Other libraries utilized are Matplotlib, Plotly, and Numpy. 

Data wrangling techniques:
We utilized excel to manually add/remove data that was either incomplete, or irrelevant to our analysis. There were a total of four rows that needed to be removed as the youtube video or video source was no longer available. 

Using the dataset, we ask the following questions: 

What are the defining characteristics of Super Bowl ads in the last 20 years?

In our analysis of Super Bowl advertising trends, we specifically highlight the defining characteristics of each advertisement from 2000-2020 in Figure 1. Among these, comedy and direct product showcases are the primary strategies employed by brands to engage viewers, likely reflecting an understanding of the event's light-hearted and diverse viewership demographic. Notably, Bud Light distinguishes itself through its significant use of comedic elements, effectively marrying its brand identity with its advertising approach to ensure memorability and viewer engagement. On the other hand, patriotism ranks as the least favored theme among the ads we analyzed. This could be attributed to its potential to narrow audience appeal, the risk of exacerbating current socio-political tensions, and the need to resonate with an increasingly international audience. These insights suggest a strategic shift by brands towards more universally appealing themes that prioritize entertainment and inclusivity over nationalistic sentiments, demonstrating our nuanced adaptation to the changing dynamics of Super Bowl viewership.

How does industry frequency in Super Bowl ads change over time? 

![image](https://github.com/lindsayraymcfadyen/superbowl-ad-analysis-project3/assets/148826786/a69d85ac-7e58-4adc-a19c-3cc1bf15c2ee)


In figure 2, the brands have been categorized into four categories: Investment, Food & Beverage, Automobile, and Alcohol. In our dataset, we had a total of 9 brands that provided goods or services. Three brands within the Food & Beverage category (Doritos, Pepsi, Coca-Cola), one within the Investment category(E-Trade), three brands within the automobile category (Toyota, Kia, Chevrolet), and two brands within the Alcohol category (Bud Light, Budweiser). Brands advertising in the category of Alcohol are present in every year of the dataset with Food & Beverage being present in all years except for the the initial year of 2000. Interestingly, the dataset that we used clearly had a lack of data within 2017 where only two advertisements were collected. Further assessment shows that the categories of Food and Beverage, and Alcohol clearly take up the majority of advertisement time and space within the data analyzed from 2000 to 2020. This alludes to the fact that during the Super Bowl, brands are trying to appeal to human consumption of commissary goods. This aspect of the Super Bowl is well documented and expressed within American cultural ideas.

How have YouTube views for Super Bowl Ads changed over time? 
	
Next in figure ? A similar graph shows the average views per year. This graph unfortunately shows little to no correlation from views to year of the ad. The only notable part about this graph is the spikes of views in certain years post youtube creation. This can perhaps be attributed to the ability to ‘go viral’ that youtube has allowed companies in recent times.  

How has the like to view ratio on YouTube for Super Bowl Ads changed over time?
 
In the figure,  all videos with 10,000 are shown as data points on a scatter plot, displaying the like to view ratio over time. A vertical dotted line illustrates when youtube became a mainstay in the social media world, and thus an estimation of when superbowl ads were being uploaded to the site soon if not immediately after airing. This dividing line shows that in the time since the video giant has become mainstream, the view to like ratio on Super Bowl ads has trended upwards in that time. This can be attributed to an increase in users on the platform, as well as the increase in users using youtube as a platform explicitly to re-watch these videos. 

How have Super Bowl Ad Youtube views changed over time for each brand?
To analyze the change of Super Bowl YouTube views over time for each brand, the view counts for each Super Bowl advertisement were gathered and depicted on bar graphs. Illustrating the year-to-year change in YouTube views offers insights into the performance of a brand's advertisement relative to previous years.  For instance, as illustrated  in the second figure, Kia's 2019 Super Bowl advertisement received the lowest number of YouTube views, whereas Kia's 2017 advertisement received the highest view count. This comparison could allow Kia's marketers to analyze the characteristics of these advertisements to inform their decisions for future Super Bowl ads. 

Limitations: The dataset we utilized lacked all advertisement data for all the years analyzed. This is clearly shown within our brand types over time chart that shows only 2 ads recorded for 2017 which clearly is not accurate. Although our dataset may not be able to give us a complete reflection of the advertisements within this time period, it does allow for us to gain insight into trends of these two decades. Another consideration that must be made for our dataset is in relation to the analysis of likes and views. Many of the videos within the dataset were uploaded at different times, and by various “unofficial” hosts. This could cause the data to be inconsistent depending on where/when the video and its respected data were collected. 

References: 
https://github.com/rfordatascience/tidytuesday/blob/2e9bd5a67e09b14d01f616b00f7f7e0931515d24/data/2021/2021-03-02/youtube.csv 
