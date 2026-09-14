# AIPI 590: ML Court (Week 5)

For this week's activity, I worked on using explainable AI techniques to defend a certain position. In this case, I was assigned to defend Case 3: Recidivism Prediction.

## Results
I used LIME and SHAP to explain Malik's prediction. The corrected model predicted no recidivism with a probability of about 0.391, compared with a baseline probability of about 0.449.

SHAP showed that Malik's limited prior convictions and lack of juvenile offenses lowered the predicted risk. The felony charge, age, and encoded race category increased the prediction somewhat. LIME showed the same general pattern using a local approximation around Malik's profile.

The two methods use different approaches and may produce different feature weights. Their agreement supports the defense argument that the model's prediction follows identifiable learned patterns. However, the model has limited predictive performance, and these explanation methods describe model behavior rather than proving causation, accuracy, or fairness. Additional fairness analysis would be necessary.