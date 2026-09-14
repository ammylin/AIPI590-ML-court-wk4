# AIPI 590: ML Court (Week 5)

For this week's activity, I worked on using explainable AI techniques to defend a certain position. In this case, I was assigned to defend Case 3: Recidivism Prediction.

## Results
I used LIME and SHAP to explain Malik's prediction. Both methods showed that Malik's limited prior convictions and lack of juvenile offenses were important factors supporting the model's low-risk prediction.

SHAP showed that Malik's predicted recidivism probability decreased from a baseline of 0.457 to 0.099. While LIME and SHAP use different approaches and may produce different feature weights, their general agreement strengthens the defense argument that the prediction is explainable.

However, these methods explain the model's behavior and do not prove causation or fairness, so additional fairness analysis would be necessary.