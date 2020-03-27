# Quantum Code Generation with Conditional-RNNs
Capstone project for Minerva Schools, Yoav Rabinovich, March 2020.

#### Abstract
A Conditional Stacked Recurrent Neural Network with GRU cells is
used to generate quantum circuits based on desired target quantum
states. The conditional network is trained on randomly sampled circuits
and their simulated output states as conditions that are introduced into
the internal memory state of the initial GRU cell. The network fails to
achieve the desired target states, possibly due to the synthesized dataset
which lacks correlations in gate placement within each circuit. An
analysis of the method and the results is provided, as well as a discussion
about possible avenues for refinement, and an overview of the subjects
of conditional RNNs and quantum circuits.
