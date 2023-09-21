Lazy FCA
A big homework to merge Lazy Learning and Formal Concept Analysis. Created for the course Ordered Sets in Data Analysis (GitHub repo) taught in Data Science Master programme in HSE University, Moscow.

Task description
Intention of the homework
This homework serves as an entry point for students into the data science world.
So it introduces students to three main topics:

Typical machine learning project:
The pipeline of loading a dataset, feature engineering, designing a new predictive algorithm, results comparison;
Lazy learning:
Predicting labels for small or rapidly changing data;
Rule-learning (on part with FCA):
Viewing data as binary descriptions of objects (instead of points in a space of real numbers).
To-do list
Basic achievements (5-6 pts.)
 Find a dataset for binary classification:
Ideal dataset would be: openly available, with various datatypes (numbers, categories, graphs, etc), with hundreds of rows;
 Describe scaling (binarization) strategy for the dataset features,
 Describe prediction quality measure best suited for the dataset
(e.g. accuracy, f1 score, or any measure that you find reasonable),
 Adapt the pipeline from lazyfca.ipynb to your task.
(Very) good solution (7-8 pts.):
 Improve the baseline algorithm:
 Achieve better asymptotic time complexity;
 Improve the runtime of examples comparison:
 Rewrite the intersections of sets into the intersection of the corresponding bitmasks. Would it make the algorithm faster?
(numpy, bitarray, and other python packages may be of help);
 Modify the algorithm to achieve better quality of predictions.
 Or simply design a new lazy algorithm to beat the baseline
in terms of algorithmic time complexity, runtime, and prediction quality;
 Compare the proposed algorithm with at least 2 popular rule-based models
i.e. decision tree, random forest, XGBoost, CatBoost in terms of runtime and prediction quality.
Perfect solution (9-10 pts.)
 Incorporate pattern structures into the pipeline to avoid the scaling (binarization);
 Test the proposed algorithm on more datasets (at least 3 others);
 Compare the proposed algorithm with at least 3 popular rule-based models.
