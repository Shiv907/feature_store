
## Create Feature store and use the latest data for prediction 

Topics covered in Code. 

1. Prepare data set and store in parquet format
2. Create an event_timestamp column to the data
3. Create a unique ID and add as a column to the data
4. Do feast init and create feature repo structure (to be modified later)
5. create feature_definition.py file inside feature repo 
6. Define data source and feature views
7. do feast apply to register and deploy features to offline store
8. load historical features using get_historical_features from offline feature store
9. Train the model using offline features
10. Use feast materialize-incremental to load features to online store
11. Get online features using get_online_features
do the prediction using the data from online feature store

## References: 

1. [Medium] (https://kedion.medium.com/creating-a-feature-store-with-feast-part-1-37c380223e2f#:~:text=With%20feast%20materialize%2Dincremental%20%2C%20the,of%20the%20most%20recent%20materialization)

2. [Feast] (https://docs.feast.dev/)



