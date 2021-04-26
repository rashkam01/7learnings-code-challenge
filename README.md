# 7learnings-code-challenge

## Challenges 
1. Being new to GCP and BigQuery sometime was spend in understanding the open datasets available in GCP, creating service account and keys, using it to access the data through querying from python notebook 
2. Limited understanding of weather data, only little time was spend in understanding the data, how the various features in the dataset affect the prediction variable "SNOW". 
3. Baseline performing than Dense, CNN, RNN models. 

## Future Work 
1. Understanding features better in Part 1, out of around 31 features finding its correlation with snow, and selecting the ones which are strongly positively or strongly negatively related to snow fall. 
2. Here only single step model is used to modelling, however, for station 725300, the data was provided from 24-01-2006 to ending 16-04-2010. The prediction was asked for 16.02.2010, therefore the correct input width, offset and label width needs to be set in order to see what is the predicted value and compare it with the actual data to see if the prediction was correct or not. 
3. The Question asks for stations between 725300 and 726300 but we have only selected 725300. This can be considered going in future. 
4. Analysis needs to be done about improving models other than Baseline to see how to make it perform better on the data. 
