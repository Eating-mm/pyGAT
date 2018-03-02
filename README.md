# Pytorch Graph Attention Network

This is a pytorch implementation of the Graph Attention Network (GAT)
model presented by Veličković et. al (2017, https://arxiv.org/abs/1710.10903).

The repo has been forked initially from https://github.com/tkipf/pygcn. The official repository for the GAT (Tensorflow) is available in https://github.com/PetarV-/GAT.

# Performances

The training of the transductive learning on Cora task on a Titan Xp takes ~0.9 sec per epoch and 10-15 minutes for the whole training. The final accuracy is between 83.6 and 84.6 (obtained on 3 different runs).

A small note about initial sparse matrices operation of https://github.com/tkipf/pygcn: they have been removed. Therefore, the current model take ~7GB on GRAM.

# Requirements

pyGAT relies on Python 3.5 and PyTorch 0.4 (due to torch.where).

# Issues/Pull Requests/Feedbacks

Don't hesitate to contact for any feedback or create issues/pull requests.
