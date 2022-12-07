# Multi-objective-Just-in-time-Software-Defect-Prediction


Boosting Multi-objective Just-in-time Software Defect Prediction by Fusing Expert Metrics and Semantic Metrics




Dataset
========
This study used 21 Java projects from the large-scale high-quality data set recently collected by Ni et al. to mitigate the impact of tangled commits on the basis of LLTC4J.The details of statistical information  can be found in Table as bellow.
![image](https://github.com/starrydays/MOJ_SDP/blob/main/G/2.png)

Result
=============
![image](https://github.com/starrydays/MOJ_SDP/blob/main/G/rq1.png)
![image](https://github.com/starrydays/MOJ_SDP/blob/main/G/rq24.png)
![image](https://github.com/starrydays/MOJ_SDP/blob/main/G/rq3.png)


Operation Guide
===================
Train the MOJ-SDP model based on expert metrics：<br>
_________
    Use only the first 14 columns in the dataset.Change the size of matrix A in ..\MODEP\fitnessLogistic_nclasses.m and ..\Project\muti_testLogistic_nclasses.m,and change the variable 'nvar' in ..\MODEP\MODEP.m to 11.
Train the MOJ-SDP model based on semantic metrics：<br>
__________
    Use only the last 769 columns in the dataset.Change the size of matrix A in ..\MODEP\fitnessLogistic_nclasses.m and ..\Project\muti_testLogistic_nclasses.m,and change the variable 'nvar' in ..\MODEP\MODEP.m to 769.

Model complementary analysis, run<br>
____________
    venn\demo1.m
Model performance evaluation, run<br>
____________
    Bar_chart.m
    
