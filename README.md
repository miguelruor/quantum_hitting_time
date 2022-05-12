# A new definition of hitting time and an embedded Markov chain in a continuous-time quantum walk
*Miguel A. Ruiz-Ortiz, Ehyter M. Martín-González, Diego Santiago-Alarcon, Salvador E. Venegas-Andraca*

### Abstract

We present and study a new probabilistic definition for the hitting time of a continuous-time quantum walk into a marked set of nodes, when measurements with respect to the canonical basis are performed according to the jump times of a Poisson process. With this new definition, we derive a formula for the calculation of the mean hitting time, based on Wald's Theorem and the stochastic process obtained from the results of the measurements. This stochastic process results in a Markov chain, whose transition matrix contains the expected values of the squared norm of the entries of a random unitary matrix, and it can be thought as a way to embed a Markov chain in a continuous-time quantum walk.

### Numerical experiment

Here we present a comparison between two methods to compute the hitting time of a CTQW in a 4x4 grid. The first method is to compute the mean hitting time with our formula, and the second method is to run $N$ simulations of the CTQW and then compute the average hitting time to the marked nodes in those simulations.