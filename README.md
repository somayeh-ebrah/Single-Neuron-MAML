# Single-Neuron-MAML

We use a single-neuron neural network as a simple example to illustrate the Model-Agnostic Meta-Learning (MAML) algorithm [1]. The goal of MAML is to learn a good initialisation of $w$, the meta model's parameters. We define a dataset and aim to train the model to obtain a good initialisation that can quickly adapt to a new task using only few data samples and updates. This setting is also formalised as a few-shot learning problem.

[1]. Finn, C., Abbeel, P., & Levine, S. (2017, July). [Model-agnostic meta-learning for fast adaptation of deep networks](https://proceedings.mlr.press/v70/finn17a/finn17a.pdf). In International conference on machine learning (pp. 1126-1135). PMLR.
