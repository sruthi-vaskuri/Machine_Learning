# Machine_Learning


### Labels
A label is the thing we're predicting - the y variable.

### Features
A feature is an input variable - the x variable. A simple machine learning project might use a single feature, while a more sophisticated machine learning project could use millions of features, specified as: x1,x2,......,xn.

### Key Points

* A labeled example includes both feature(s) and the label. 
* Labeled examples: {features, label}: (x, y)
* In our spam detector example, the labeled examples would be individual emails that users have explicitly marked as "spam" or "not spam."
* An unlabeled example contains features but not the label.
* In the spam detector, unlabeled examples are new emails that humans haven't yet labeled.
* Unlabeled examples: {features, ?}: (x, ?)

### Models
A model defines the relationship between features and label. 

* Training means creating or learning the model. That is, you show the model labeled examples and enable the model to gradually learn the relationships between features and label.

* Inference means applying the trained model to unlabeled examples. That is, you use the trained model to make useful predictions (y'). 
