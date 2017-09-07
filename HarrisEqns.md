Let $m_{i,j}$ and $n_{i,j}$ be the respective coefficients of $M$ and $N$.
Let $\beta_l$ denotes the coefficient associated with the $l^{th}$ pair (here
we have: $\beta_{1,2}, \beta_{1,3}, \beta_{2,3}$)

Communities *k*, species *i* and abiotic variable *j* ($x_j$):


$$\Phi(k) = \sum_i \sum_j m_{k,i}a_{i,j}x_{j} + \sum_l \beta_{l} n_{k,l}$$


$$\text{logit}(P(X = S_k)) = \mathcal{N}(\Phi(k), \sigma)$$

IIRC, Harris does not care about the variance...
So, to me the model is a linear one...
