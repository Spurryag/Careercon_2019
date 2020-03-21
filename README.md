# The Problem
Help robots recognize the floor surface they’re standing on using data collected from Inertial Measurement Units (IMU sensors).

# My Approach

Using a Random Forest to classify the data after converting the data from Euler angles to Quarternions and rebalancing the data using SMOTE.

# My Result
The Random Forest model managed to achieve a multiclass accuracy of 0.7 (366th out of 1449 participants - top 26%).

