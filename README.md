# Multi-objective-Just-in-time-Software-Defect-Prediction


Boosting Multi-objective Just-in-time Software Defect Prediction by Fusing Expert Metrics and Semantic Metrics




Dataset
========
This study used 21 Java projects from the large-scale high-quality data set recently collected by Ni et al. to mitigate the impact of tangled commits on the basis of LLTC4J.The details of statistical information  can be found in Table as bellow.
![image](https://user-images.githubusercontent.com/28954173/208236564-e8f2a321-0cdc-4672-baaa-f518ca1c603a.png)

Result
=============

![image](https://user-images.githubusercontent.com/28954173/208235311-e7d462f7-622b-4246-983f-86ca3c5568fb.png)


![image](https://user-images.githubusercontent.com/28954173/208236627-c1f9dd4e-2d11-424e-a765-ce242f3f337e.png)


![image](https://user-images.githubusercontent.com/28954173/208235346-13bb4e99-0b8d-4b89-b92d-7f3229cf4584.png)



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

Environment
===================
Intel(R) Core(TM) i5-10200H CPU @ 2.40GHz   2.40 GHz
MATLAB R2018b
