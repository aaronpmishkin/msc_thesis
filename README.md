# Interpolation, Growth Conditions, and Stochastic Gradient Descent

This repo contains the draft of my MSc. thesis. The main contributions are the following: 

1) a generalized notion of interpolation for stochastic optimization problems;
2) a careful complexity analysis of stochastic gradient descent under interpolation, both with a constant step-size and with a stochastic Armijo line-search; and 
3) an analysis of Nesterov's accelerated gradient method (under interpolation) using the estimating sequences framework.

----

Many of the results developed here are improved versions of theorems from the following two papers:

1) [Fast and Faster Convergence of SGD for Over-Parameterized Models and an Accelerated Perceptron](https://arxiv.org/abs/1810.07288): 
   - constant step-size SGD;
   - Nesterov's accelerated gradient method. 
2) [Painless Stochastic Gradient: Interpolation, Line-Search, and Convergence Rates](https://arxiv.org/abs/1905.09997): 
   - SGD with a stochastic Armijo line-search.
   
   
## Acknowledgements 

I am extremely fortunate to have been supervised by [Mark Schmidt](https://www.cs.ubc.ca/~schmidtm/) throughout my masters.

I am also greatly indebted to my colleagues and friends [Sharan Vaswani](https://vaswanis.github.io/), [Frederik Kunstner](https://fkunstner.github.io/) and [Si Yi (Cathy) Meng](https://www.cs.ubc.ca/~mengxixi/).
