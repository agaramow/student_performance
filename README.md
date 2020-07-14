## Using Data Mining to Predict Secondary School Student Performance, P. Cortez and A. Silva (2008)
### Computational Statistics Course 2020 

### The Project
The authors of the presented paper show how Data Mining (DM) methods can be applied in the educational sector. Their motivation is based on two main developments: the low educational performance of Portuguese students at the European level and the increased use of DM methods in social science. They argue that DM methods may provide an understanding of the underlying dynamics in the education sector due to their potential prediction power. To demonstrate this, the authors use four DM techniques: Decision Trees, Random Forest, Neural Network and Support Vector Machines to predict the performance of Portugese students. The supervised learning of the methods use data which combines administrative and self reported data on achieved scores in the two core subjects, Maths and Portuguese and socio-economic background. They show that although the prediction of the students' performance is dominated by the past performance, there are other relevant features, e.g., number of absences, parent’s job and education, alcohol consumption, which help to explain students' performance. Finally, they conclude that more efficient prediction tools can be developed to aid the educational school resource management.

Following the argument of Cortez and Silva (2008), this notebook aims to compare the prediction performance of three tree based methods from our class: Bagging, Random Forest and Boosting versus the well known OLS/ Logistic regression. After evaluating and comparing the results from the different methods with each other and the results of Cortez and Silva (2008), I will assess their relative performance following the three measures: (1) prediction accuracy measured by the test MSE, (2) variable importance, and (3) interpretability. To check the robustness of the results, I first, model the achieved scores as a binary, five-level classification (European convention) and a 20-point grading scale response.

### Course Instructor
* Prof. Lena Janys

### Authors
* Adelina Garamow 

### Main package used for replication
* xxx

### Additional Material
* xxx

### Main References and Links
* Cortez, P., & Silva, A. M. G. (2008). Using data mining to predict secondary school student performance.
* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An introduction to statistical learning (Vol. 112, p. 18). New York: springer.


