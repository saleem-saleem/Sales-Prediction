# Sales-Prediction
Problem Statement:
Many seasons have sales that are considerably higher or lower than the average income. If the corporation is unaware of these seasons, it risks losing a significant amount of money. One of a company's most important plans is to forecast future sales. Sales forecasting offers a corporation an idea for stocking shelves, calculating revenue, and selecting whether or not to make a new investment. Another benefit of forecasting future sales is that hitting specified goals early in the season may boost stock prices and investors' opinions. In addition, failing to meet the planned objective might have a substantial negative impact on stock values. And that will be a major issue, particularly for Reliance as a large corporation.The goal of this project is to create a model that forecasts retail sales. Reliance authorities may select their future plans using this model, which is critical for stock management, revenue calculation, and determining whether or not to make new investments.

Benefits:

To determine seasonal demands and take action for this
Protecting from money loss because achieving sales targets can have a positive effect on stock prices and investors' perceptions
Forecasting revenue easily and accurately
Managing inventories
Do more effective campaigns

Objectives:

Understanding, Cleaning and Exploring Data: The first challange of this data is that there are too much seasonal effects on sales. Some departments have higher sales in some seasons but on average the best departments are different. To analyze these effects, data divided weeks of the year and also holiday dates categorized.

Preparing Data to Modeling: Boolean and string features encoded and whole columns encoded.

Random Forest Regressor: Feature selection was done according to feature importance

ARIMA/ExponentialSmooting/ARCH Models: Second challange in this data is that it is not stationary. To make data more stationary taking difference,log and shift techniques applied.
Findings:
Although some departments has higher sales, on average others can be best. It shows us, some departments has effect on sales on some seasons like Thanksgiving.
It is same for stores, means that some areas has higher seasonal sales.
Stores has 3 types as A, B and C according to their sizes. Almost half of the stores are bigger than 150000 and categorized as A. According to type, sales of the stores are changing.
As expected, holiday average sales are higher than normal dates.
Top 4 sales belongs to Christmas, Thankgiving and Black Friday times. Interestingly, 22th week of the year is the 5th best sales. It is end of May and the time when schools are closed.
Christmas holiday introduces as the last days of the year. But people generally shop at 51th week. So, when we look at the total sales of holidays, Thankgiving has higher sales between them which was assigned by Walmart. But, when we look at the data we can understand it is not a good idea to assign Christmas sales in data to last days of the year. It must assign 51th week.
January sales are significantly less than other months. This is the result of November and December high sales. After two high sales month, people prefer to pay less on January.
CPI, temperature, unemployment rate and fuel price have no pattern on weekly sales.
More detailed finding can be found in notebooks with explorations.

Future Improvements:
Data will be made more stationary with different techniques.

More detailed feature engineering and feature selection will be done.

More data can be found to observe holiday effects on sales and different holidays will be added like Easter, Halloween and Come Back to School times.

Markdown effects on model will be improved according to department sales.

Different models can be build for special stores or departments.

Market basket analysis can be done to find higher demand items of departments.
