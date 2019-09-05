# Multineuron-Shunting-Inhibition-Network

The code is meant to simulate and examine the properties of additive and shunting
networks. A network of ten cells will be the basis for the simulation. In the additive model, the
effects of excitatory and inhibitory inputs are supposed to add linearly. The output firing rate of
the presynaptic neuron is used. However, it is difficult to account for threshold and saturation
effects within this model. Within a steady state, the firing rate depends heavily on the chosen
weights.

The feedforward shunting model is more complex, allowing for the creation of a better
neural network model. It can simulate more biological properties and has a wider dynamical
range because it is derived from the Hodgkin-Huxley equation. In addition, shunting networks
possess automatic gain control properties which ultimately make it capable to generate that wide
dynamical range. The shunting model can also be modulated with additional terms that represent
a distance-dependent receptive field.
