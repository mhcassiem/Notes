### Data pre-processing flow:
- Data pre-processing
	- importing data
	- clean data
	- split into training and test sets
- Modeling 
	- build model
	- train model
	- make predictions
- Evaluation 
	- calculate performance metrics
	- verdict

### Training data and test data

Before creating a model datasets are usually split into a training set and a test set.

Usually training set is 80% of the data, test set is 20%

Training set is used to create model and test set is used for evaluation. 


### Feature scaling

Sometimes different data attributes have wildly different value scales.
Eg. salary number vs age
In cases like these it is useful to scale the attribute values to a uniform scale.

##### This is feature scaling.

Feature scaling is applied to columns

Two types
1. Normalization
	1. $$\frac{X-X_{min}}{X_{max}-X_{min}}$$
2. Standardization
	1. $$\frac{X-\mu}{\sigma}$$