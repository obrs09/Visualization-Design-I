# Multidimensional Visualization: Coffee Sales Dataset

## Dataset

This project uses the **Coffee Sales Dataset** from Kaggle:
[https://www.kaggle.com/datasets/anassarfraz13/coffee-sales-dataset](https://www.kaggle.com/datasets/anassarfraz13/coffee-sales-dataset)

The dataset contains 3,530 coffee sales transactions from a café,  with following features:

**hour of the day** : The hour when the purchase occurred

**cash type** : Payment method used

**money** : The amount of money spent on the purchase

**coffee name** : The type of coffee or drink purchased

**Time of Day** : Morning, Afternoon, Evening, etc

**Weekday** : The day of the week on which the transaction occurred

**Month name** : month when the transaction was recorded

**sorting of day or month** : weekdays and months sorting

**Date** : date of the transaction

**Time**: Exact time of purchase

## Description of paragraphs

### first plot:

By seperated in two subplot. The upper one shows the total revenue of each month, with x axis of each month and y axis of total money. The lower one shows the number of transaction of each month.

### second plot

Pie plot of total revenue by coffee type. each color of pie plot represents differect coffee

### third plot

Heatmap of average spending by hour and weekday, the x axis is hour of the day, y axis is day of the week. Color shows the average money spending. This allows quick identification of peak business times and weekday trends.

### fouth plot

Bar plot of revenue of milk and no milk product in Morning, Afternoon and Night. Latte, Milk, Cappuccino, Hot Chocolate, Mocha, Cocoa will be catorize as Milk, the other will be No Milk. This plot shows the revenue both Milk and No milk in three time period.

## Future work

Consider more time seriers types of data, like how does revenue change from beginning to the end of the month

Consider about special case. such as the festival, only 28 days in Feb, etc.

