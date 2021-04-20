<h1 align="center"> Cassandra-Udyam'21</h1>

<p align="center">
    <img height="250" width="1000" src="Cassandra images/comp.png">
</p>

This Repo Contains the notebook and presentation of Our Approach which we used and presented during the competition Cassandra organised by Udyam'21.
In the competition we have to identify the defaulter based on the demographics data and payment_history.<br>

For more info about competition visit - [Here](https://www.kaggle.com/c/cassandra-udyam21)

Presentation of Our Approach - [Here](https://www.canva.com/design/DAEb9SgEPfU/PyGTl3_zXOAIScjpzl86Cg/view?utm_content=DAEb9SgEPfU&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

[Code](cassandra-21-creatorz.ipynb)

<b>A brief description of our Approach</b><br>
We used feature Aggregation on payment history and combined it with the original demographics data and trained LGBM model with optuna hyperparameter tuning.
Our method can serve as a good technique for handling class imbalance in cases of defaulter predictions.

## Additional Analysis and Innovation
We showed a method which utilised the concept of covariate shift and proved that the distribution of train/test is dissimilar to quite a good extent, which yield failures related to trusting of cross validation scores. Our this analyis about data stood among the others.

## References

 - [Best notebook to start](https://www.kaggle.com/yassineghouzam/titanic-top-4-with-ensemble-modeling)
 - [Train/Test Similarity Analysis using covariate shift](https://www.kaggle.com/shikhar1/train-test-similarity)
 - [Optuna Tuning](https://towardsdatascience.com/how-to-make-your-model-awesome-with-optuna-b56d490368af)
 - [LGBM](https://medium.com/@pushkarmandot/https-medium-com-pushkarmandot-what-is-lightgbm-how-to-implement-it-how-to-fine-tune-the-parameters-60347819b7fc)
 - [Aggreation and Magic Features](https://www.kaggle.com/cdeotte/xgb-fraud-with-magic-0-9600) (**Credits - Chris Deotte**)
  
## Achievement

**We got 1st position in the event while applying this approach.**

<h2 align = "center"> Visulaisation Snapshots </h2>

<p align="center">
    <img height="250" width="300" src="Cassandra images/Beta_C.png">
    <img  height="250" width="300" src="Cassandra images/Beta.png"><br>
    <b>Beta (left) and Beta with labels(right)</b><br>
    <img height="250" width="300" src="Cassandra images/Alpha.png">
    <img  height="250" width="300" src="Cassandra images/Delta.png"><br>
    <b>Alpha with labels(left) and Delta with labels(right)</b><br>
 </p>

