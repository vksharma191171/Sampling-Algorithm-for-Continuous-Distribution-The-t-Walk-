# Sampling-Algorithm-for-Continuous-Distribution-The-t-Walk-
In this project work, we discuss "t-walk", the MCMC sampler for continuous distribution that requires no tuning. The sampler is introduced by J. A. Christen and C. Fox
in his paper " A General Purpose Sampling Algorithm for Continuous Distributions (the
t-walk) 2010". They apply Metropolis-Hasting algorithm and choose proposal with the
help of four moves according to t walk design which we will discuss in details.They choose
a proposal distribution in such a way that an algorithm is invariant to scale and affine
transformation to the state space.

In general, this algorithm is only a small factor less efficient than optimally tuned algorithm but performed very well in comparison to general random walk M-H samplers that
are not tuned for a particular problem ( we later compare these two with some examples).
Also, this algorithm remains effective for target distribution for which correlation structure is very different in different regions of state space.
Thus, this MCMC sampling algorithm neither contains adaptivity nor tuning parameter,
and we can sample from a target with arbitrary scale and correlation structure. As t-walk
construct as M-H algorithm on product space, so it converges under mild conditions.
