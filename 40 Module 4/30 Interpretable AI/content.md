
## Interpretable AI

As you've read in the writing assignment from the previous module, current AI
legislation also provides the right to an explanation in the case of an
automated decision. And in many applications being able to explain why a
certain prediction was made, can be very valuable, as it can help humans to
assess whether they think that prediction is correct, or even desirable for the
system to make, (in the case of biases, for instance).

As you might imagine, making the predictions of a neural network explainable is
actually very difficult to do. This type of model is also called a *black box*
model, where a sample goes in, a prediction comes out, but you can't really say
much about what exactly happens in the middle. There are just way too many
neurons, each with their own weights, to really explain why the network made
that exact prediction.

This has led to recent research into how to make AI systems explainable, which
has resulted in quite a few different methods to generate an explanation for a
black box model. For example:

* Determining what features in the testing sample, or which specific samples
from the training data where relevant for this prediction
* Interpreting or visualizing the internal structure or weights of the model in
some way as to give insight in what has actually been learned.
* Learning an an interpretable model that comes very close to the results of 
the original black box model for (some part of) the problem and then interpret
that model instead.

To get a better introduction to these types of methods, we'll read some
sections from the
[Interpretable Machine Learning Book](https://christophm.github.io/interpretable-ml-book/)
by Christoph Molnar. Start by reading sections:

* Interpretability: 2.0, 2.1, 2.2
* Interpretable Models: 4.0, 4.4
* Model-Agnostic methods: 5.0 and 5.1

from the book before you continue with the rest of the assignment.

Cynthia Rudin from Duke Unversity wrote an interesting article advocating a
differnt position, namely to stop using black box models altogether, whenever
possible, for any situation where explanations might be needed. Read the
article linked here:

[Cythia Rudin - Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead](https://arxiv.org/abs/1811.10154).


Claims from the article. Agree or disagree and why:

1. Learned interpretable models with high agreement are not explanation
	
	An inaccurate (low-fidelity) explanation model limits trust in the explanation, and by extension, trust in the
	black box that it is trying to explain. An explainable model that has a 90% agreement with the original model
	indeed explains the original model most of the time. However, an explanation model that is correct 90% of the
	time is wrong 10% of the time. If a tenth of the explanations are incorrect, one cannot trust the explanations, and
	thus one cannot trust the original black box.


2. Existance of interpretable models with similar performance

	If the pattern in the data was important
	enough that a black box model could leverage it to obtain better predictions, an interpretable model might also
	locate the same pattern and use it. Again, this depends on the machine learning researcher’s ability to create
	accurate-yet-interpretable models.


	Consider that the data permit a large set of reasonably accurate
	predictive models to exist. Because this set of accurate models is large, it often contains at least one model that
	is interpretable. This model is thus both interpretable and accurate.


3. Mandates on interpretability should be put into place for companies using black box models

	no black box should be deployed when there exists an interpretable model with the same level of performance.

	organizations that introduce black box models would be mandated to report the accuracy of interpretable modeling methods
