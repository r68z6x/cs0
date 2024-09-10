java cRussell Cooper
September 4, 2024
Exercise #1: Due September 9, 2024
Consider the asset pricing model from the ﬁrst lecture. The value of the asset is the solution to:
q(d) = d + βEd0
|dq(d
0
) ∀d ∈ D (1)
1 Solution
Write Matlab (Julia, Fortran, etc.) code to solve this functional equation using value function iteration. To do so,
you will have to specify parameters for the discount factor and the process for dividends.
1 Show how your solution
depends upon the discount factor by graphing the function q(d) for two diﬀerent values of β.
2 Estimation
You will receive a data set that has a time series for the asset value and for the dividends, i.e. (代 写program、C++，Python
代做程序编程语言qt, dt) for t = 1, 2, 3, ...T.
2.1 Project 1: Estimate Π Matrix
Using the data, estimate the Π matrix using the count approach. As you can see from the data, there are only two
states for dividends.
2.2 Estimate β
Estimate β using SMM, picking one data moment. The moment could be the mean of qt, as in class, or another
moment. Create a graph of the simulated and actual moments as a function of β.
1You can specify D and the transition matrix directly or take an AR(1) representation of dividends and using the Tauchen procedure,
create a discrete representation of the stochastic process. See the discussion AC chpt. 2.
1

         
加QQ：99515681  WX：codinghelp
