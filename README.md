# ML-School-by-REU-Data-Science-Club-Project
Forecasting in-store sales (sales) based on the database of Corporación Favorita, a large equatorial food retail store using CatBoost, XGB, LGBM

File Descriptions and Data Field Information

train.csv:
* The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
* store_nbr identifies the store at which the products are sold.
* family identifies the type of product sold.
* sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
* onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

test.csv:
* The test data, having the same features as the training data. You will predict the target sales for the dates in this file.
* The dates in the test data are for the 15 days after the last date in the training data.

sample_submission.csv:
* A sample submission file in the correct format.

stores.csv:
* Store metadata, including city, state, type, and cluster.
* cluster is a grouping of similar stores.

oil.csv:
* Daily oil price. Includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and it's economical health is highly vulnerable to shocks in oil prices.)

holidays_events.csv:
* Holidays and Events, with metadata.
