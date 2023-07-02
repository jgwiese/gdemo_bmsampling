# demo bayesian modeling sampling
The purpose of this project is to demonstrate the implementation and results of the optimization of a probabilistic model.
Since this model has two continuous latent variables, multiple quantities can be inferred by bayesian inference and 
marginalization.

![alt text](https://raw.githubusercontent.com/jgwiese/prob_model_sampling/main/.msc/latent_w.png "Latent Space w exploration and Posteriors")
**Figure 1**: Exploration of latent space w (left) on a regular grid on [-2, 2] x [-2, 2]. Each cell belongs to a 2D conditional probability distribution p(x|w).
Bayesian inference can also be performed for a shape X, so that the posterior distributions for p(w|X) were calculated for all ten shapes from the data set (right).
The maximal values match to the locations of the shapes on the left side.
<br>
<br>

![alt text](https://raw.githubusercontent.com/jgwiese/prob_model_sampling/main/.msc/latent_z.png "Posteriors of z")
**Figure 2**: Bayesian inference on the shape-model. The posterior distributions p(z|x, w) (right) for samples x from a shape of a digit (left) can be approximately evaluated.

For basic usage and more functionality demonstration have a look at the 
[jupyter notebook](https://github.com/jgwiese/prob_model_sampling/blob/main/learning.ipynb).
You can also contact me for details regarding the model and the optimization objective derivation. 
