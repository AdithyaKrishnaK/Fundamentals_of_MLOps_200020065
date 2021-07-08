# Assignment 1

**In the notes of Week 1, we compared & contrasted MLOps with DevOps. In this question, you need to understand what is meant by the term AIOps, & then contrast it with MLOps.**

AIOps (Artificial Intelligence for IT Operations) uses multi-layered technology platforms that automate and enhance IT operations through AI and ML. While MLOps is used to deploy
and maintain ML models, AIOps use ML and AI to troubleshoot and optimise IT operations (MLOps is a pathway to create new models, AIOps is more for maintenance).
AIOps have three main processes in a cycle,
* Service management
* Performance management 
* Automation

Basically, it is aggregating operations data from various divisions and then presenting the problems, recommendations to the user and finally to resolve the problems.

Source: https://www.bmc.com/blogs/what-is-aiops/

**Interpretable Machine Learning is another concept that has attracted lot of attention recently & is promoted by most of the MLOps frameworks. Explain what it means for a linear 
regression model to be interpretable.**

Interpretable Machine Learning tries to explain its outputs. This helps in easier debugging and estimating the reliability of the model. For linear regression model, this would look like weights of different features. The weights determine the contribution of a feature on the overall prediction. The higher the weights the higher is the importance of a feature and vice versa. The variance of estimated weights also plays a role, the more the variance is, the less important the feature is. All this can be put together using weight plots. Note that it is important to normalize the data before feeding it to the model. 

Source: https://towardsdatascience.com/interpretable-machine-learning-1dec0f2f3e6b?utm_source=pocket_mylist
