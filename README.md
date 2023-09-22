 # Prediction-of-Car-insurance
The Business and the Stakeholders wants to determin the likelyhood of a client to claim from insurance

## The source of the data
The data was sourced from Kaggle website,  https://www.kaggle.com/datasets

## A description of the data
Original dataset consist of 10000 rows, after droping the duplicate rows came down to 9229 and 19 columns.It has
float64(6), int64(5), object(8)
## analytical insights from your data analysis.
  ![image](https://github.com/Noks06/Prediction-of-Stroke-and-Car-insurance-/blob/main/speedingandpastaccidents.png)

The above graph show that speeding is the driving factor of accidents, as the graph clearly stats that more speeding violation causes more accidents that will lead to claiming from insurance.As the graph shows 18 speeding violation has a whooping more than 8 accidents. 

  ![image](https://github.com/Noks06/Prediction-of-Stroke-and-Car-insurance-/blob/main/Driving%20under%20the%20influence.png)

The graph above has shown that married people are more likely to drive under the influence of a substance.There are many factors that lead to them taking the substance, it could be a circumstances that most married people are facing, family obligation.

The metrics for your best model
  ![image](https://github.com/Noks06/Prediction-of-Stroke-and-Car-insurance-/blob/main/Logistic%20Regression%20with%20Grid.png)


Logistic Regression model has the highest accuracy prediction of 83 percent and it has correctly predicted that 428 client will claim from insurance with the low of 
137 that were predicted to have claim when they did not claim. Again with 250 that were predicted not going to claim , unfortunately they did claim.with low result 
of FP and FN the model will do better job on prediction with little  help of hyper tune the parameters.


  ![image](https://github.com/Noks06/Prediction-of-Stroke-and-Car-insurance-/blob/main/KNN%20with%20Grid.png)

KNearestNeighbour is another model that came close to Logistic Regression predictions with 81 percent accuracy, The model predicted correctly that 1443 clients will not claim and 419 will claim, with 189 that were predicted to claim but they did not claim and 259 that were predicted to not claim but they actually did claim.  

## A summary with a recommendations
I would recommend two models and those are Logistic Regression and KNearestNeighbour, both of these model showed accuracy of their prediction to be 83 and 81 percent respectively on their test set with lower False Negetive of 250 and 259 respectively, where clients were predicted that they will not take up claim but they actually did. Having lower False Negetive on will actually portrail good result to the cumpany.
