# Reliance-Sales-Prediction

Reliance's data scientists gathered sales data for 1559 goods across 45 outlets in various cities from 2010 to 2012. In addition, certain characteristics of each product and retailer have been determined. The goal is to create a prediction model and determine the sales of each product in each store. Create a model for Reliance to use to analyse and forecast outlet production sales. The following are the properties of each section: the related store (recorded as a number), the comparing division (81 offices, each entered as a number), the date of the first day of that week, departmental week after week deals, the store measure, and a Boolean value indicating whether there is a major event within the week. The important holidays are Diwali, Eid, and Christmas-New Year. A parallel set of highlights for each section, including Customer Cost List, unemployment rate, temperature, gasoline cost, and special markdowns, may be included in addition to the previously listed features.

PROBLEM STATEMENT

Many seasons have sales that are considerably higher or lower than the average income. If the corporation is unaware of these seasons, it risks losing a significant amount of money. One of a company's most important plans is to forecast future sales. Sales forecasting offers a corporation an idea for stocking shelves, calculating revenue, and selecting whether or not to make a new investment. Another benefit of forecasting future sales is that hitting specified goals early in the season may boost stock prices and investors' opinions. In addition, failing to meet the planned objective might have a substantial negative impact on stock values. And that will be a major issue, particularly for Reliance as a large corporation.The goal of this project is to create a model that forecasts retail sales. Reliance authorities may select their future plans using this model, which is critical for stock management, revenue calculation, and determining whether or not to make new investments.

OBJECTIVES

•	Understanding, Cleaning and Exploring Data: The first challange of this data is that there are too much seasonal effects on sales. Some departments have higher sales in some seasons but on average the best departments are different. To analyze these effects, data divided weeks of the year and also holiday dates categorized.

•	Preparing Data to Modeling: Boolean and string features encoded and whole columns encoded.

•	Random Forest Regressor: Feature selection was done according to feature importance

•	ARIMA/ExponentialSmooting/ARCH Models: Second challange in this data is that it is not stationary. To make data more stationary taking difference,log and shift techniques applied.


FINDINGS AND OBSERVATIONS

•	Although some departments has higher sales, on average others can be best. It shows us, some departments has effect on sales on some seasons like diwali festival.

•	It is same for stores, means that some areas has higher seasonal sales.

•	Stores has 3 types as A, B and C according to their sizes. Almost half of the stores are bigger than 150000 and categorized as A. According to type, sales of the stores are changing.

•	As expected, holiday average sales are higher than normal dates.

•	Top 4 sales belongs to Diwali, Christmas-newyear and Mahanavami times. Interestingly, 22th week of the year is the 5th best sales. It is end of May and the time when schools are closed.

•	Christmas holiday introduces as the last days of the year. But people generally shop at 51th week. So, when we look at the total sales of holidays, diwali has higher sales between them which was assigned by Reliance. But, when we look at the data we can understand it is not a good idea to assign Christmas sales in data to last days of the year. It must assign 51th week.

•	January sales are significantly less than other months. This is the result of November and December high sales. After two high sales month, people prefer to pay less on January.

•	CPI, temperature, unemployment rate and fuel price have no pattern on weekly sales.


BENEFITS OF THIS PROJECT

•	To determine seasonal demands and take action for this

•	Protecting from money loss because achieving sales targets can have a positive effect on stock prices and investors' perceptions

•	Forecasting revenue easily and accurately

•	Managing inventories

•	Do more effective campaigns

