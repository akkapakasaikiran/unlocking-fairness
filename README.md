# Unlocking Fairness: A paper presentation

This is a presentation I made for [CS689](https://sites.google.com/site/harishguruprasad/teaching/topics-in-ml-iitb-aug-2021), a course I took in my final year at IITB. 

Title: Unlocking Fairness: a Trade-off Revisited

Astract: The prevailing wisdom is that a model’s fairness and its accuracy are in tension
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

You can find the paper [here](https://papers.nips.cc/paper/2019/hash/373e4c5d8edfa8b74fd4b6791d0cf6dc-Abstract.html).

## Credits

* [Hakim El-Hattab](https://twitter.com/hakimel) for the simple awesome [Reveal.js](https://github.com/hakimel/reveal.js)
* [Martino Mensio](https://twitter.com/MartinoMensio) for his guide on how to use Reveal.js as a Git submodule in [this](https://martinomensio.medium.com/how-to-host-reveal-js-slides-on-github-pages-and-have-a-tidy-repository-1a363944c38d) blog post

## License

* MIT Licensed as per Reveal.js itself

