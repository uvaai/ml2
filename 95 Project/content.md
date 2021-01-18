# Project

This project is completely optional, as your final grade for the "ML project"
will only depend on the combination of your grades for the previous 2 modules.
However, as there is about a week left, we'd like to suggest some interesting
directions in AI to further explore.

If you'd like to still try a machine learning project this last week, you're
very welcome too. Know that originally we planned a month for a project, so
you'll probably not be able to complete it, but you'll still gain a lot more
experience in applying AI in a project of your own. As this portion is
ungraded, it doesn't matter if you pick something too ambitious and are not
able to complete it.

In addition to a project, we see a couple of other options, which you might be
more likely to complete in a week. Whichever topic you pick, we'd suggest you
do these in a team of around 3 people, but it is entirely up to you of course,
as there are no hard constraints. The main directions we'd suggest are:

### Machine Learning project

This will probably be a classification or regression task for which you have to
process the data and build a model with the best performance on a validation /
test set according to some metric. We'd suggest you try and explore models from
[scikit-learn](https://scikit-learn.org/stable/index.html) or
[tensorflow](https://www.tensorflow.org/api_docs/python/tf/keras) if you're
going for a neural network approach.

For datasets, [Kaggle](https://www.kaggle.com/) provides many, many challenges
you might take up. If you'd like a recommendation, we'd suggest the [plankton
classification challenge](https://www.kaggle.com/c/plankton-challenge/overview)
from a few years ago. You can of course discuss any other projects topics you
might want to try with us.

### Visualization project

Alternatively, you may want to experiment with processing and visualizing data,
and seeing what interesting things you can find, instead of having an exact
classification goal in mind. Again, you might look for data sets on
[Kaggle](https://www.kaggle.com/) or you could even try to visualize some data
from own studies.

Also, there are many COVID-19 dataset floating around at moment, so you could
try and visualize the spread of the virus or maybe even effectiveness of
certain measure. Good starting points might be
[novel corona virus 2019 dataset](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset)
or alternatively [COVID-19 open research challenge](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge).

### Machine Learning extended topics

Even though we've covered a lot of ML algorithms, there are still many more topics
to explore. For this project you should pick a class of algorithms we've not
covered yet, study them on your own and see if you can get these algorithms to
learn on a simple problem. You should currently have enough of a general
background to find relevant material for most classes of algorithms, although
we still might be able to point you in a specific direction if needed. There
are two classes we would suggest as options:

Language models using neural networks. With CNN's we've covered the image
recognition side of deep learning, but another very large branch is in text
processing. Specifically we'd suggest you start looking at word embeddings like
word2vec, *Recurrent* Neural Networks (RNN's) and LSTM's, which give the model
some form of "memory" about the previous word when processing the next word.

Reinforcement learning. This is an area of machine learning we haven't covered
at all, different from supervised / unsupervised learning, where you try to
learn a whole *sequence* of actions to gain a reward. This means it is
particularly well suited to learning to play games, where you might need quite
a few actions before you score a point. The most common algorithm in RL is
Q-learning and combining it with neural networks is called DQN (Deep Q
Networks), which can learn to play a game of Pong. The [OpenAI
Gym](https://gym.openai.com/) offers a framework in which you can try to learn
to play these games.

### Writing assignment extended topics

Lastly, you could pick another writing assignment topic and dive into that.
This can again be any topic we've not covered yet. One suggestion we might make
is to take a look at the recent developments around *explanainable* and
*interpretable* AI. In many critical applications, knowing why a model has
predicted something is more and more becoming almost as important as the
accuracy of the prediction itself. Some resources and articles to get you
started:

* [Interpretable ML book](https://christophm.github.io/interpretable-ml-book/)
* [Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead](https://arxiv.org/abs/1811.10154)
* [Explanation Methods in Deep Learning: Users, Values, Concerns and Challenges](https://arxiv.org/abs/1803.07517)

## Starting your project

You can start by picking one of the suggested directions and then looking for
teammembers or form a team and then decide on a topic together. If you're still
looking for or accepting other teammembers, you can make a post on the [Ed
forum](https://edstem.org/us/courses/2334/discussion/) using the `ML Project`
tag. You can of course do any of these topics alone, and there is official no
maximum group size either, although we would recommend *about 3 students* per
team.

If you have made a team and selected a topic, please **send us a short
message** to inform us. Additionally, if enough of you would want to, we could
do very informal final presentation session, where any team that would like,
can share what they've done / learned this week. So, please also let us know if
you'd like to participate in this.

