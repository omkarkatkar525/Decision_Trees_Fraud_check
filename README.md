# Decision Trees:

```sh
Decision Trees: It is a Non-Parametric Model.
It is Logical Tree kind of Representation.
3 Impotant Paramters of Decision tree.
1. Root Node: columns comes inside the node.
2. Edges: division inside each column.
3. Leaf Node: Finalize output.

Information Gain(IG): In order to choose the root node we pick the column as a root node with high IG.

Entropy: In order to decide whether the edge should be another branch or leaf.
If Entropy = 0 , Pure Branch (leaf node)
If Entropy >0, impure Branch

Hyperparameter: In order to construct a tree/ any algorithm we need certain parameters we call these hyperparameters if we are tweaking these hyperparameters the model will give better results.      

GrideSearchCV: Rather than trying with all the Hyperparameters manually every time we take all the parameters and pass them into the grid search CV. It gives the parameter which will give the best results.

```

## Performance Metrics:
```sh
Performance Metrics are help us in deciding whether model is good or not.
  1. Accuracy: 
                Accuracy = (TP+TN)/(TP+FN+FP+TN)
          Out of total predicted values how many values are predicted correctly.
  2. Recall/TPR:
                  Recall= TP/(TP+FN)
          From all positives values ,how many are actually predicted as positives values.It is individual class Accuracy.
  
  3. Specitivity/TNR:
                   Specitivity = TN/(TN+FP)
           From all negative values how many are actually predicted as negative values.
  4. Precision:
                    Precision=TP/(TP+FP)
           From all predicted positives values, how many are actual positives values. It is individual class Stability.
  5. F1-score:
                    F1-score = 2*Recall*precision/(Recall+Precision)
           out of all observations how many are predicted incorrectly.
```

## Data Used :
```sh
fraud_check: prepare a model on fraud data 

``` 

## Programming:
```sh
Python
```

<!-- CONTACT -->
## Contact :

Name - Omkar katkar  
Mail ID - omkarkatkar525@gmail.com


Datasets used in project are present in Repository detail.
