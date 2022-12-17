# Multi-objective-Just-in-time-Software-Defect-Prediction


Boosting Multi-objective Just-in-time Software Defect Prediction by Fusing Expert Metrics and Semantic Metrics




Dataset
========
This study used 21 Java projects from the large-scale high-quality data set recently collected by Ni et al. to mitigate the impact of tangled commits on the basis of LLTC4J.The details of statistical information  can be found in Table as bellow.
![2](https://user-images.githubusercontent.com/28954173/208234552-3a40a538-c781-403b-bb4c-5bdd205450c1.png)

Result
=============

![rq1](https://user-images.githubusercontent.com/28954173/208233989-e3fdf38c-862e-4e97-8f24-4416dbc343b5.png)


![rq24](https://user-images.githubusercontent.com/28954173/208234069-4849ce0c-af1e-428e-99be-eb4c7174cb36.png)


![rq3](https://user-images.githubusercontent.com/28954173/208234071-edf08ce7-375b-43fd-a17e-d73f0e9ad144.png)



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
    
