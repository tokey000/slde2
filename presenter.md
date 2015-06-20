Introduce My App
========================================================
author: Tokey
date: Sun Jun 21 00:40:30 2015
autosize: true

Side bar Panel
========================================================

The APP is used to predict the weight of children from their age and height. 

In the side bar Panel,there are 3 parts you can select or input value:
* **First part**  
  Select the gender of the children you decide to analyse;  

* **Second part**  
  Input the age and height which you want to use to predict the chlid's weight;
 
* **Third part**  
  Give the number of observations to view;
  

The result of the Summary
========================================================

The Summary gives the details of the data under the gender you selected.  

It gives the following Basic statistics:
- Min  
- 1st Qu  
- Median  
- Mean  
- 3rd Qu  
- Max  

The result of the Regression
========================================================

The regression part give the relationship between the weight and age,height under different gender.  

For example,when you chose gender 'M',the result of regression model are:

```
(Intercept)         age      height 
  1.9181597   0.4505176   0.4069768 
```

The result of the Prodict and Observations
========================================================
* **predict**  
    Give the age and height ,the predict will give the predicted weight;

* **Observations**  
  The the number of Observations to show is depending on the value you input in "Number of observations to view".


