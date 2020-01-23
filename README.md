# Machine-Learning-model-using-LIME
Model interpretability is very important. If non-technical people cannot understand the machine learning models, it is not helpful for the companies even though machine learning models are really powerful. LIME is a python library which tries to solve for model interpretability by producing locally faithful explanations. 

## The definition of Lime
LIME ( Local Interpretable Model-agnostic Explanations )is a novel explanation technique that explains the prediction of any classifier in an interpretable and faithful manner by learning a interpretable model locally around the prediction.

## What has LIME had to offer on model interpretability?
1. A consistent model agnostic explainer [ LIME ].
2. A method to select a representative set with explanations [ SP-LIME ] to make sure model behaves consistently while replicating human logic. This representative set would provide an intuitive global understanding of the model.
LIME explains a prediction so that even the non experts could compare and improve on an untrustworthy model through feature engineering.

### Interpretable 
It should provide qualitative understanding between the input variables and the response. It should be easy to understand.
### Local Fidelity
It might not be possible for an explanation to be completely faithful unless it is the complete description of the model itself. Having said that it should be at least locally faithful i.e it must replicate model’s behaviour in the vicinity of instance being predicted.
### Model Agnostic
The explainer should be able to explain any model and should not make any assumptions about model while providing explanations.
### Global perspective 
The explainer should explain a representative set to the user, so that the user has a global intuition of the model.
