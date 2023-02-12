# startups_succeed_or_fail
A work in progress using ML techniques on a large open source data set from Kaggle (~65,000 entries) about startups to determine whether they will succeed or fail. Link to Kaggle data set is here: https://www.kaggle.com/datasets/yanmaksi/big-startup-secsees-fail-dataset-from-crunchbase.

Given it is a work in progress, comments are not yet present. These will be added in time. Code includes examples of exploratory data analysis, geographical plots, correlation plots, and filling in missing data.

So far I've deployed Logistic Regression, but the nature of the data suggests that this is too rudimentary (underlying relationships are not linear and obviously distinct enough) - a Random Forest, Linear SVC and other approaches. Neural Net if necessary, however this could lead to major overfitting as the data for particular countries and sectors is sparse.

I've also done some normalisation, but further normalisation may be required to stop overweighting of variables.

All the changes described above will come in later versions of the code, along with detailed commenting.
