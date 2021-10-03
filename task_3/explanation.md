More complicated networks (more layers and parameters) are used for complicated taks, but for simple dataset they are just overfitting.

Chosing optimizer (Adam, SGD and so on) depends on your task and training strategy. I prefer choosing RMSProp for almost all my models.

LR depends on optimizer mostly. LR is one of "true" hyperparameters which you will always tune.