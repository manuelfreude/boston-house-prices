# Boston house price prediction using Decision Tree Regressor
## Python project summary

- Explored data incl. min, max, mean, median, standard deviation, definition of r2 performance metric
- Visualized potential decision tree depths and respective training and testing score, see graphic below
- Evaluated model performance with grid search and cross validation and implemented model
- Predicted value of three selected houses based on relevant attributes

## Decision Tree learning performance

![Performance](https://github.com/manuelfreude/boston-house-prices/blob/master/Decision_Tree_Regressor_Depth_Performance.png)

Based on the graphs, I would choose a depth=3 for continuing with the model with lines converging at a score of about 0.8. The score of depth=1 is quite low, indicating an underfitting, even though the lines are rather converging. A depth=6 and depth=10 shows rather not converging lines. The results need to be confirmed by gridsearch to also check further depths not viewed here.
