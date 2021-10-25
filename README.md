# Credit_Risk_Analysis

## Overview of Project
This project’s objective is to analyze a large amount of data in the Financial Tech sector to predict credit risk. 
The deliverables for this project are:

*	Use Resampling modules to predict credit risk.

* Use the SMOTEENN Algorithm to predict credit risk.		
							
*	Use Ensemble Classifiers to predict credit risk.


## Software
Python, Pandas Jupyter notebook and Machine Learning Modules. 


## Results 


### Use Resampling modules to predict credit risk.



![image](https://user-images.githubusercontent.com/86136535/138615681-509bcd59-a321-4412-86fa-7cb90ebfe859.png)




![image](https://user-images.githubusercontent.com/86136535/138615452-9e0da3f5-70a8-4b75-8e22-3dd503bed781.png)

Accuracy Score – 66%

Precision - The model’s precision is low (1%), meaning that the model’s ability to measure positive classification is not reliable. 

Recall – The model presented a good level of positive instances (74%), confirming that almost three quarters of its classification were correctly identified.

F1 – Shows a low balance between precision and sensitivity, the best score for F1 is 1.0.








![image](https://user-images.githubusercontent.com/86136535/138627578-fecb1ebe-552c-4436-8622-d69acdcb951a.png)

![image](https://user-images.githubusercontent.com/86136535/138615799-988c43a5-3def-4063-99cf-cc889dc61fac.png)


Accuracy Score – 65%

Precision - 1%, ability to measure positive classification is not reliable. 

Recall – 62%, shows weak ability to correctly identify positive instances.

F1 – Low balance between precision and sensitivity.


### Undersampling


![image](https://user-images.githubusercontent.com/86136535/138627099-0ae6ca1d-a2ad-4725-82f9-d91fb48bd267.png)


![image](https://user-images.githubusercontent.com/86136535/138627129-366ad73c-7a05-48a6-a267-56243ceae88f.png)


Accuracy Score – 54%

Precision - 1%, ability to measure positive classification is not reliable. 

Recall – 69%, shows weak to good ability to correctly identify positive instances.

F1 – Low balance between precision and sensitivity.


### Combination


![image](https://user-images.githubusercontent.com/86136535/138627222-8e7aa25d-f7ed-424e-8e60-ecad02db80a4.png)


![image](https://user-images.githubusercontent.com/86136535/138627238-30725680-a24e-4ad9-a4d4-d89ee936c66a.png)


Accuracy Score – 68%

Precision - 1%, ability to measure positive classification is not reliable. 

Recall – 77%, shows strong ability to correctly identify positive instances.

F1 – Low balance between precision and sensitivity.


### Use Ensemble Classifiers to predict credit risk.



![image](https://user-images.githubusercontent.com/86136535/138627290-3bdf2069-86ce-42f5-917d-328cbb8e5dab.png)


![image](https://user-images.githubusercontent.com/86136535/138627304-5839ba72-d96a-4893-8847-df938891620b.png)


Accuracy Score – 68%

Precision - 88%, reliable ability to measure positive classification. 

Recall – 37%, weak ability to correctly identify positive instances.

F1 – medium balance between precision and sensitivity.


![image](https://user-images.githubusercontent.com/86136535/138627348-6205dbd4-fac2-4603-b848-f00664af5b3a.png)

![image](https://user-images.githubusercontent.com/86136535/138627359-6fee096b-1c15-49f8-92a0-aaf740e5a983.png)


Accuracy Score – 93%
Precision - 9%, ability to measure positive classification is not reliable.
Recall – 92%, shows strong ability to correctly identify positive instances.
F1 – Low balance between precision and sensitivity.


### Summary

Due to the lack of balance in the components being analysed, I would not recommend the use of these models for credit risk. The results under the resample classifiers showed a fair accuracy score, however their precision and F1 scores were low. On the other hand, the combination sample model (SMOTEEN) presented a good accuracy score and strong ability to identify positive instances but again its precision and balance between precision and sensitivity was low.












