# SVM-outlier-detection

a) Use the following function to generate a custom dataset:

make_classification (n_samples=100000, n_features=2, n_informative=2,
n_redundant=0, n_repeated=0, n_classes=2, n_clusters_per_class=1, weights=
[0.995, 0.005], class_sep=0.5, random_state=42).

By doing this you will generate 100,000 synthetic data such that 99.5% of the data
belongs to class 0 and 0.05% belongs to class 1. In fact, our class 1 is synthetic
outliers. split the dataset into 80% training data and 20% validation data.

b) What is one-class SVM and how can it be used in outlier detection? run the one-class SVM
on training data. (Set the nu, kernel and gamma).

c) Make outlier predictions on the validation dataset. Which of the metrics such as precision,
recall, etc. can
