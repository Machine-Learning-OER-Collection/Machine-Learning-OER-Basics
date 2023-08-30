<!--
SPDX-FileCopyrightText: 2023 Machine-Learning-OER-Collection
SPDX-License-Identifier: CC-BY-4.0
-->
## Confusion matrix for a multi-class classification

For a multi-class confusion matrix the variables TP, TN, FP and FN have to be calculated for each individual class.

Structure of the matrix:
* True classes are in the rows.
* Predicted classes are in the columns.

For class 1 the value of the true positive predictions is found in the first field of the first row and the first column. The other entries in the first row show all false negative predictions. All false positive predictions are found in the other entries of the first column. In the rest of the fields are the true negative predictions.    

<br>

![multi-class confusion matrix](../img/confusion_matrix_multi_class.svg)

_Reference:  
Confusion matrix for a multi-class classification by ischmahl from the repo [machine-learning-OER-Basics](https://github.com/Machine-Learning-OER-Collection/Machine-Learning-OER-Basics) is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)._
