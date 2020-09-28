# LSTM-based-Price-forecasting-of-wallmart-sales-data

* Historical Sales Dataset of 45 wall mart stores located in different region
* Each store contains number of departments 
* In stores.csv
      -we have anonymized information about the 45 stores, indicating the type and size of store.
* train.csv
  * Historical training data, which covers to 2010-02-05 to 2012-11-01. 
    * Attributes are	
      * Store - the store number
      * Dept - the department number
      * Date - the week
      * Weekly_Sales -  sales for the given department in the given store
      * IsHoliday - whether the week is a special holiday week
* Features.csv
  * Contains additional data related to the store, department, and regional activity for the given dates. 
      * Attributes are 
        * Store - the store number
        * Date - the week
        * Temperature - average temperature in the region 
        * Fuel_Price - cost of fuel in the region
        * MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
        * CPI - the consumer price index
        * Unemployment - the unemployment rate
        * IsHoliday - whether the week is a special holiday week

* The LSTM Architecture used is 
![](picture4.png)
