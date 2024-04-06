# Neural Networks

These videos by Andrew outline what a neural network looks like, and give some
good intuitions on why it is such a useful model. They should be a good first
introduction into what neural networks are exactly. These videos do not yet
cover how exactly to train a neural network.

#### Notation

These videos use a slightly different notation than we use in the course, which
changes a few things:

1. The parameter vector $w$ is called $\theta$ (theta) here.
2. The bias term is included in the parameter vector as $\theta_0$.
3. The input vector $x$ is expanded to also contain $x_0$, which is a constant input always set to $1$. This constant "feature" get multiplied with the $\theta_0$ bias, and adds the bias term that way (instead of just adding it separately, like we've done before).

This means you might see a Logistic Regression using just two features and
a linear decision boundary as:

$$g(\theta^Tx)$$

where

$$\theta = \left[\begin{array}{c} \theta_0 \\ \theta_1} \\ \theta_2 \end{array} \right]\ ,\ x = \left[\begin{array}{c} x_0 \\ x_1} \\ x_2 \end{array} \right]$$

which, when you write out the vector multiplication, is the same as

$$g(\theta_0x_0 + \theta_1x_1 + \theta_2x_2)$$

If we apply the $3^{rd}$ rule stating $x_0$ is always just $1$, this becomes

$$g(\theta_0 + \theta_1x_1 + \theta_2x_2)$$

and then applying the $2^{nd}$ rule, we can replace $\theta_0$ with the bias term $b$

$$g(b + \theta_1x_1 + \theta_2x_2)$$

Finally, we can apply the $1^{st}$ rule, replacing $\theta$ with $w$

$$g(b + w_1x_1 + w_2x_2)$$

which should be the version of the equation you are familiar with.

Note that, conceptually, these notation do exactly the same thing, as this really just a slightly different way of writing the same Logistic Regression.

### Neural Network Representation: Non-linear hypothese

![embed](https://youtube.com/embed/SGEroEKFbnY)

## Backpropagation: Training a neural network

The algorithm to learn the weights of a neural network based on training data
is called *backpropagation* and is quite a difficult algorithm to completely
understand. Introducing backpropagation in its general form will be one of the
main topics of the *next* neural networks module.

Here, for a high level overview of what backpropagation tries to do and
how neural networks end up being used in practice, we'll refer to these
introductory videos by *3blue1brown*.

### Deep Learning: But what is a Neural Network?

![embed](https://youtube.com/embed/aircAruvnKk)

### Deep Learning: Gradient descent, how neural networks learn

![embed](https://youtube.com/embed/IHZwWFHWa-w)

