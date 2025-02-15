# The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).


## Data Exploration and Cleaning
- Dataset looks clean (no  null values)
- Some of the features contain unknown values which need to be dealth with
- euribor3m, nr.employed, emp.var.rate all have correlation values greater than threshold value(0.9)
- People between age 25 and 50 have subscribed the term deposit
- Campaign was targeted at adult between age 25-50

## Modeling
- Among all the models tested, RandomForestClassifier showed hightest accuracy of 0.9409718958548736

## Next steps
- Use more modeling techniques like PCA, GridCVSearch, tune hyper parameters to evaluate model performance
