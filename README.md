# ML-in-Physics-and-Astronomy
This repository is provided to store the final project of machine learning in physics and astronomy.

A high-energy collision in particle physics is called an event that is simulated in this study. We
generate post-collision data, including energy-momentum 4-vector, and mass of new particles, with
the Monte Carlo approach based on system energy conservation and relativistic dispersion relation
in particle physics. Then, we train an MLP regression network to predict masses of particles given
a corresponding 4-vector. The network could achieve RMSE 6.20 and 6.28 for the event particles
that are promising for the masses with means about 100. Additionally, we propose a conditional
Variational Auto Encoder to facilitate the generation process whose input is the masses of the
regressor. The cVAE model outputs the synthetic 4-vector and the result indicates that the method
can be help in generating data fast.
