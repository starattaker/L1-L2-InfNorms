# L1-L2-InfNorms
So, while studying numerical optimization I got this question , Does the convergence of a particular optimization algorithm depend on what norm with stopping criterion used ? So took a minute to find out .

Yes, convergence can depend on the norm used, as different norms measure the gradient’s size differently. This affects when the algorithm decides to stop (based on how small the gradient is under that norm), the path it takes toward the minimum, and the number of steps it needs to converge. While the final result may remain the same, the efficiency and behavior of the optimization process can vary depending on the chosen norm.
