## Gobind Sagar Lake Water Monitoring using GiS Techniques

1. At first we have used Google Earth Engine to extract data for the various water parameters for the lake eg pH, Dissolved Oxygen, Dissolved Organic Matters, Nitrate, Phosphorous, Salinity, Chlorophyll, Suspended Matter, Turbidity, Temperature using the Google Earth Engine API using the information of the various electrospectral bands.

2. After that we are preprocessing the dataset. The dataset didn't contain any null values but it contains some of the highly correlated features so we dropped that features. After that we assigned the labels to the records of the dataset 0 means it is fit for drinking , 1 means it needs treatment and 2 means it is bad. Surprisingly we didn't any record that contains the label 0 meaning that the water is not fit for drinking purpose.

3. After that we did the model training and we have used Random Forest to classify the data points.