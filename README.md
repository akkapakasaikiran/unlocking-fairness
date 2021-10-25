# Unlocking Fairness: A Paper Presentation

[This](https://akkapakasaikiran.github.io/unlocking-fairness/) is a paper presentation I made for [CS689](https://sites.google.com/site/harishguruprasad/teaching/topics-in-ml-iitb-aug-2021) (*Machine Learning: Theory and Methods*), an amazing course I took in my final year (Autumn 2021) at IITB. It was offerred by Prof. [Harish](https://sites.google.com/site/harishguruprasad/home) Guruprasad Ramaswamy, who was visiting IITB for a semester.

**Title:** Unlocking Fairness: a Trade-off Revisited [[link](https://papers.nips.cc/paper/2019/hash/373e4c5d8edfa8b74fd4b6791d0cf6dc-Abstract.html)]

**Astract:** The prevailing wisdom is that a model’s fairness and its accuracy are in tension
with one another. However, there is a pernicious modeling-evaluating dualism
bedeviling fair machine learning in which phenomena such as label bias are appropriately
acknowledged as a source of unfairness when designing fair models,
only to be tacitly abandoned when evaluating them. We investigate fairness and
accuracy, but this time under a variety of controlled conditions in which we vary the
amount and type of bias. We find, under reasonable assumptions, that the tension
between fairness and accuracy is illusive, and vanishes as soon as we account for
these phenomena during evaluation. Moreover, our results are consistent with an
opposing conclusion: fairness and accuracy are sometimes in accord. This raises
the question, might there be a way to harness fairness to improve accuracy after
all? Since many notions of fairness are with respect to the model’s predictions
and not the ground truth labels, this provides an opportunity to see if we can improve
accuracy by harnessing appropriate notions of fairness over large quantities
of unlabeled data with techniques like posterior regularization and generalized
expectation. We find that semi-supervision improves both accuracy and fairness
while imparting beneficial properties of the unlabeled data on the classifier.
