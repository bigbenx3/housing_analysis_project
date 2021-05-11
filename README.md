

# King County Real Estate


**Author**: [Benny Zhu](mailto:bennyzhu@buffalo.edu)

## **Overview**
 
This project analyzes King County housing data from 2014 and 2015 in order to make recommendations as to which factors most significantly impact the sale price of a house.

## **Business Problem**


King County Real Estate has hired us to investigate which features of a home have the greatest effect on price.

* They would like us to make a model to predict housing prices.
* From that model, they would like to know which factors have the largest effect on price.




## **Data**

The main source of data we will work with is the King County Housing Sales dataset, 2014 to 2015.
    kc_house_data.csv


## **Methods**

For the purposes outlined above, we will use a variety of methods and modules that include:

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Statsmodels
* Sklearn

## **Results**

* The average home price was $476, 9027. 

* On average, our predictions were off from the real price by +/- $89,840. 


### **Living Area**
!["scatterplot for price and living space sqft"](./images/housing_project_images/price_and_house_living_space_new_5_11_21.png)
As the living area of a house increases. So does the price.



### **Location**
!["scatterplot colored inferno format of price and location King County, WA area"](./images/housing_project_images/price_and_location_final.png)
The location of a house, particularly, above 47.55°N.



### **Quality**
!["barplot of different colors for price and grade of home"](./images/housing_project_images/price_and_house_grade_new_5_11_21.png)
The quality of the house itself (its grade) makes a big impact. Higher the grade, the higher the value of the home.





## **Conclusions about Model**

Descriptive analysis and modeling reveal which factors contribute most to housing prices: 

● Increase Living Area(in square feet) 

● Buy homes in regions specified (47.55 15°N to 47.7 15°N) (Or 
    maybe homes outside of this region will likely be more affordable) 
    
● Upgrade the quality of your home

## **Next Steps**

* The data we were provided was from 2014 to 2015. And such outdated data may not give us the optimal insights relevant to 
  today's housing situation

* We should be able to get a lot more out of the location data, with further analysis, incorporating data relevant to the 
  zipcode so there is a better determination for prices that can be expected in a more defined area.

* Also, streamlining the methods of getting a more fitted model without going too far into "overfitted" territory. 
  Like I've mentioned before, there is a happy medium in there.

* The most obvious next step is to try out new modeling techniques.  While linear regression is a good start, there are many 
  other techniques that I believe could help make better predictions.  Of particular interest to me in this context are 
  Polynomial Regression and Weighted Least Squares, that might be promising.

## **For More Information**


For additional info, I can be reached at [bennyzhu@buffalo.edu](mailto:bennyzhu@buffalo.edu)


## Repository Structure

```
├── data
├── images
├── README.md
├── kc_housing_pres.pdf
└── kings_c_housing.ipynb
```