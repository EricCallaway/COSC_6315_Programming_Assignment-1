# COSC_6315_Programming_Assignment-1

Part 01

Q: Which model gives you the best fit for the data?
A: Model 02 gave the best fit for the data in my experiment. Model 01 had an accuracy of 39.82% and Model 02 had an accuracy of 45.37%.

Q: Why is this model giving you the best result?
A: I'm not entirely sure. If I had to guess I would assume that the Lot area, year the house was built, and the year the house was most recently renovated would be better metrics for accurately predicting the house price versus the year the garage was built, the number of cars that can fit in the garage, and the garage square feet in area. I would assume that the reason model 01 performed worse is becuase there is more variance in the scalar values of model 01's X features than model 02's. For example there is more of a difference in the years homes can be built versus the number of cars you can fit in a garage. 

Q: Do you think a different dataset can change the choice of the best model?
A: Absolutely, the differences in the percentage of correct predictions were very close. A different data set can most definitely tell a completely different story of what model is a better fit.

Q2: Which value of 𝜃0 𝜃1 Will minimize the cost function most?
A: Manipulating theta0 (y-intercept) will have a greater effect on minimizing the cost function. Manipulating theta1 (the slope) shows incremental changes, while manipulating theta0 (y-intercept) shows much larger changes in the total error.
