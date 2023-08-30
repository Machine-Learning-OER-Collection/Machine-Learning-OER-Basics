<!--
SPDX-FileCopyrightText: 2023 Machine-Learning-OER-Collection
SPDX-License-Identifier: CC-BY-4.0
-->
## Coefficient of determination (R squared)

The coefficient of determination is a measure of the linear correlation between data points.

The range is between 0 and 1.

* A value close to 1 means, that there is a good model fit.
* A value close to 0 means, that there is a poor model fit.

#### Code example:
    from sklearn.metrics import r2_score
    print(f"R squared: {r2_score(linear_regression.predict(X_reg_test), y_reg_test)}")

(Reference: Example code for a linear regression model by ischmahl from the repo [machine-learning-OER-Basics](https://github.com/Machine-Learning-OER-Collection/Machine-Learning-OER-Basics) licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).)

<br>

>![linear equation](../img/R^2_for_1.svg)

<br>

>![linear equation](../img/R^2_for_0.5.svg)

<br>

>![linear equation](../img/R^2_for_0.svg)

_Reference:  
Coefficient of determination by ischmahl from the repo [machine-learning-OER-Basics](https://github.com/Machine-Learning-OER-Collection/Machine-Learning-OER-Basics) is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)._
