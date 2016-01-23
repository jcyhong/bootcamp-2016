**********************
Ordinary Least Squares
**********************

Compute the least squares coefficients of a linear regression model.

Brief Summary of the Least-squares Method
-----------------------------------------

The idea of the least squares is to minimize the :math:`L^2` loss function with respect to :math:`\beta`:
:math:`\sum_{i = 1}^n (y_i - x_i^T \beta)^2`.

This is equivalent to solving the normal equation for :math:`\beta`: :math:`X^T  X\beta = X^T y`.
