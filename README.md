# ACM Research coding challenge (Fall 2022)

This project attempts to give you the deal type based on the interior design, comfort, performance, value for money, exterior styling, reliablility, and min/max MPG's. 

An example use case would be when you are trying to decide on a car but don't want name and branding to interfere with which car is *actually* better in terms of the deal.

##Walk-through of the code

The data is passed into a dataframe and then manipulated to where only the data needed remains in the dataframe. From there, the data is split into X and y lists, and further split into training and testing X and y lists (for a total of 4 lists). From there, 6 scikit learn classification models are imported and tested to see which model results in the highest accuracy (in this case, random forest classifier). The RandomForestClassifier is trained again and then values are inputted to determine an output.
