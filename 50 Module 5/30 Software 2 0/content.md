## Software 2.0

This module we've returned to the topic of neural networks, as they are
currently by far the most influential machine learning models. According to
some, they're even *more* than just a very good ML model. Read the blog post by
Andrej Karpathy on this topic linked below:

[Software 2.0 - Andrej Karpathy](https://karpathy.medium.com/software-2-0-a64152b37c35)

Karpathy mentions several disadvantages of software 2.0, namely
interpretability of the learned results and sensitivity to biases present in
the training data, both of which we've covered extensively in previous writing
assignments. Another potential disadvantage he mentions, is one we've not yet
seen before, so we'll dive into it more for this assignment. Karpathy writes
that the fact these networks are susceptible to adversarial examples highlights
their unintuitive nature.

To get a better understanding of what exactly adversarial examples are, we'll
continue reading the *Interpretable ML* book by Christoph Molnar. Adversarial
examples are strongly related to counterfactual explanations, so we'll start
there. Read sections *6.1.0, 6.1.1.0 and 6.1.1.1* from that chapter:

[Counterfactual Explanations](https://christophm.github.io/interpretable-ml-book/counterfactual.html)

Next, we'll continue with the chapter on Adversarial Examples. Read the
complete chapter here:

[Adversarial Examples](https://christophm.github.io/interpretable-ml-book/adversarial.html)

**Optionally**, if you want more detail on some of the adversarial attacks
described in that chapter, we've linked the papers for these below:

* **Toaster Patch**: [Adversarial patch - Brown et. al (2017)](https://arxiv.org/abs/1712.09665)
* **3D-printed turtle**: [Synthesizing robust adversarial examples - Athalye et. al (2017)](http://proceedings.mlr.press/v80/athalye18b.html)
* **One pixel attack**: [One pixel attack for fooling deep neural networks - Su et. al (2019)](https://arxiv.org/abs/1710.08864)

For the writing assignment this week, you should argue how big of a
disadvantage or risk you think the existence of these types of adversarial
attacks is to the potential emergence of the "software 2.0" stack, i.e. using
neural networks to learn to solve problems, instead of having programmers write
explicit code to solve them:

Do you think the overal disadvantage caused by potential adversial attacks is
small or large compared to advantage of using software 2.0 instead of 1.0? Are
there any applications where you think the potential risks might be *too* large
to use to switch to software 2.0? How do the risks of these systems compare
to the normal security risks of traditional software (i.e. software 1.0)?
