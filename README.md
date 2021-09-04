![image](https://user-images.githubusercontent.com/74994512/132086803-ccc1c1f8-c600-4deb-bfda-f881f9b59540.png)


# Water Potability Check
Water quality refers to the chemical, physical, and biological characteristics of water based on the standards of its usage.Potability Testing ensures the safety of the homes well water supply. Drinking water, also known as potable water, is water that is safe to drink or use for food preparation.


# Problem Statement
Based on the features given in the dataset need to predict the predility of water. Predility is 1 the water is safe to drink, if it is 0 then it is unsafe to drink.

# Real world/Business Objectives and Constraints
1. The cost of a mis-classification can be very high
2. No strict latency concerns.
3. Interpretability is partially important


# Data Overview
1. Water potablity data consists of 10 columns those are : 'ph', 'Hardness', 'Solids', 'Chloramines', 'Sulfate', 'Conductivity', 'Organic_carbon', 'Trihalomethanes', 'Turbidity', 'Potability
2. It has 3276 rows.

# Performance Metric
1. Accuracy
2. Confusion matrix
3. Precisiion and Recall


# Distribution of data points among classes of potability





![image](https://user-images.githubusercontent.com/74994512/132086962-247e2d0f-831b-4104-9f4f-761cf50f8c2d.png)



![image](https://user-images.githubusercontent.com/74994512/132087071-ca31c82b-4ac3-4b12-bd5f-121ab8cb64ba.png)







It looks like most of the water is non potable, as the number of count and factors which effects potability of water is more. And by calculation it is found that more than 50% of water is non potable water.

# Result

![image](https://user-images.githubusercontent.com/74994512/132088605-17bba8ff-5e82-4ebb-bb5f-d180614d92d3.png)






Models SVC AND Random_Forest both gave the accuracy of 67.24% 


Recall from both model are as follows
1) Random-Forest:

    '0':0.86
    
    '1':0.45
    
2) SVC:

     '0': 90
     
     '1': 37
 
Considering recall and accuracy_score, SVC found to be better model as compared to all other algorithms.


Precision and Recall holds a top priority while selecting the best model.
