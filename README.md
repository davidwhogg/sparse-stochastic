sparse-stochastic
=================

Hogg's sandbox for working out stochastic optimization in problems of variable sparsity.

The idea is to generate some fake data with astronomical-imaging-like sparsity and connectedness.
We can use these fake data to test whether stochastic methods work or work efficiently without modification
when the sparsity is heterogenous across the parameters.
A key idea (from Dilip Krishnan) is to make sure that, in at least one case, the problem is exactly convex,
so algorithms have no excuse if they don't converge to the optimum.