
# American Personal Consumption Expenditures by Type of Product

## An analysis of consumer food and beverages purchased for off-premises consumption over 40 years

Though cereal grabbed headlines as having unprecedented sales in unprecedented times, was that the standout story of 2020 personal consumption in the United States? 
Items outside of grocery staples saw a significant increase in 2020, not just Cereal. A further exploration will reveal interesting details about the growth of other products in 2020 Including alcoholic beverages, sweets and coffee, tea and other beverage materials. This analysis will show that we can develop different and sometimes opposing stories depending on the data presented and how it is aggregated. 

#### The intended audience
This exploration is intended as a base level visual illustration of the growth rates of each category of consumable products over the time of data, to give the audience an understanding of the overall top categories and the trends that have changed between 1960 and 2020.
Secondly these visualizations focus specifically on 2020 total sales by category and the changes and growth in comparison to 2019 and how these views can change the data story.

View the exploration [here]: (https://public.tableau.com/views/TrendsinUSPersonalConsumptionExpendituresbyTypeofProduct/Millionsspent?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

#### Description of the dataset Personal Consumption Expenditures
The dataset used for this analysis is Personal Consumption Expenditures by Type of Product originally comes from the Bureau of Economic Analysis and was brought to the wider attention when it was used in the [Bloomberg article]
(https://www.bloomberg.com/opinion/articles/2021-02-24/beyond-grape-nuts-cereal-makers-had-a-very-weird-year)

Details about the data set include that it contains Personal Consumption Expenditures on food and beverages purchased for off-premises consumption, this confirms that the data excludes any premises such as restaurants or cafes. Also that the measures are in millions of dollars; quarters and months are seasonally adjusted at annual rates.

There are four columns in the data set.
The first is category of product, there are 11 unique values, these vary in the frequency, due to the variation in the sub-category. There are 20 unique values in the sub- category column and these are not evenly distributed throughout the category column. Six of the category values match with only one sub-category, two categories match with a total of two sub-categories, two categories match with three sub-categories and one category matches with four sub-categories.  Though this appears to be a complicated matter to determine if there is any missing data throughout the dataset, we can determine that all data is present because each subcategory appears an equal number of times, 745.

There are 14,900 unique values in the Millions of Dollars column (excluding the header). 
There are no missing values throughout the data set. However, when analyzing the column containing the month and year it becomes apparent that the dataset is missing the total yearly information for 2021. Each year, 1959 - 2020, holds a count of 240 unique values (12 months of data for 20 subcategories of product) where 2021 has only 20. There is only data for January 2021, to remove the possibility of skewing analysis the 2021 data will be filtered from the results. 

You can view the original data set[here](https://data.world/makeovermonday/2021w12)
And my exploratory analysis [here] (https://public.tableau.com/views/ExploratoryAnalysisofPersonalConsumptionExpendituresbyType/Average?:language=en-US&:display_count=n&:origin=viz_share_link)

#### Foreseeable challenges
There are no foreseeable challenges related to the data set, it should provide a good example of the ability to story tell with data on a simplistic level. 
The challenges faced when working on this analysis was for the most part a time constraint, with a limited amount of time to explore the data and develop a base level understanding and visualization. Given more time to research to develop further domain knowledge could also provide greater insight into the statistics that could be involved when analyzing expenditures specific to personal consumption.
Further investigations that would be of interest given more time would be to connect a dataset that contains American disposable income levels, to explore if those coincide with food and beverage trends, for example, do grocery staples remain consistent and categories that fall outside of staples (alcohol, sweets, etc) rise and fall with income? 

Resources used to create table calculations
https://www.vizwiz.com/2017/08/month-vs-avg-month.html
And Tableau community forms 
https://community.tableau.com/s/question/0D54T00000C68ozSAB/calculating-a-growth-rate-between-two-given-years


