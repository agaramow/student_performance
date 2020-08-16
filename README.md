## Using Data Mining to Predict Secondary School Student Performance, P. Cortez and A. Silva (2008)
### Computational Statistics Course 2020 

### The Project
The ability to predict students' performance is useful to optimize schools' resource management. Cortez and Silva (2008) use demographic, social and performance data on Portuguese students to show how Data Mining can be applied in the educational sector. They use supervised machine learning algorithms such as Random Forest to predict the performance of students in two core subjects, Mathematics and Portuguese. They conclude that Data Mining methods provide high predictive accuracy and uncover important variables which affect the performance of students. This notebook, joins the discussion on the adequate use of Data Mining methods in the educational sector by exploring the question if and in how far Random Forest outperforms Bagging. As a basic reference, both methdos are compared to a simple predictor which predicts the last available observation for the final score. The goal is to predict students' final score in Mathematics, using the three methods. The Mean Squared Error and the Average Prediction Error are used to evaluate the performance of the three prediction methods. The application of Random Forest and Bagging on the training data shows that Bagging outperforms Random Forest and RF provides an even lower prediction accuracy than the simple predictor. The reason is that the data provides few variables with a strong singnal for the final score and many variables with a low signal. To demonstrate this, the notebook conducts a simulation study where different subsamples of variables are considered for the training data. The simulation shows that Baggig outperforms Random Forest when the data contains few predictors with a strong signal and few predictors with a low signal. Finally, this study highligths the importance of the adequate application of statistical learning tools. This excersise can be performed analogeously for the Portuguese score.

### Course Instructor
* Prof. Lena Janys

### Author
* Adelina Garamow 

### Main package used for replication
* randomForest, MASS, plyr

### Main References and Links
* Cortez, P., & Silva, A. M. G. (2008). Using data mining to predict secondary school student performance.
* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An introduction to statistical learning (Vol. 112, p. 18). New York: springer.

### Additional Material
* Janys, L. https://github.com/LJanys/CompStat, 16.08.2020, 10:32
* Breiman, L. "Random forests." Machine learning 45.1 (2001): 5-32.
