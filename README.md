# An adaptive approach to deep Q-learning
(just an idea right now...**NOT USABLE!**)

1.) Make an autoencoder for states.
2.) Use outputs from the encoder portion to train a deep Q Network (or variant such as ddqn or deuling dqn)
3.) Move layer from encoder to dqn, add more neurons with small weights, and keep training to learn a more specialized encoding for the dqn.


