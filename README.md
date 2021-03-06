# Game-Sky

This is a resource about game playing with reinforcement learning, game theory and so on.

This project will gather newest papers and classify them gradually.(f.e. neurips 2018)

It will be updated continuously, welcome to contribute to us!.

## reinforcement learning base 
[Theory](rl-base/theory.md)

[Tutorials](rl-base/tutorials.md)

[platforms](rl-base/platforms.md)

[code](rl-base/code.md)

[demos](rl-base/demos.md)

[Applications](rl-base/applications.md)


## counterfactual regret mimization(game theory)
focus on texas hold'em and so on 

[cfr](cfr.md)
### open source library
[cppcfr](https://github.com/achao2013/cppcfr)

## deep reinforcement learning games
include alpha go series

[deep-rl](drl.md)


## newest papers(wait to reasign)
### NeurIPS 2018
#### model-based
  - Sample-Efficient Reinforcement Learning with Stochastic Ensemble Value Expansion. [paper](https://arxiv.org/pdf/1807.01675.pdf)
  - Data-efficient model-based reinforcement learning with deep probabilistic dynamics models. [paper](https://arxiv.org/pdf/1805.12114.pdf)
  - Iterative Value-Aware Model Learning. [paper](http://papers.nips.cc/paper/8121-iterative-value-aware-model-learning.pdf)
  - Data center cooling using model-predictive control. [paper](https://papers.nips.cc/paper/7638-data-center-cooling-using-model-predictive-control.pdf)
#### model free
  - Breaking the Curse of Horizon: Infinite-Horizon Off-Policy Estimation. [paper](https://arxiv.org/pdf/1810.12429.pdf)
  - Representation Balancing MDPs for Off-Policy Policy Evaluation. [paper](https://arxiv.org/pdf/1805.09044.pdf)
  - Simple random search provides a competitive approach to reinforcement learning. [paper](https://arxiv.org/pdf/1803.07055.pdf)
#### value function approximation
  - Non-delusional Q-learning and value iteration. [paper](https://papers.nips.cc/paper/8200-non-delusional-q-learning-and-value-iteration.pdf)
#### policy gradient
  - Actor-Critic Policy Optimization in Partially Observable Multiagent Environments. [paper](https://arxiv.org/pdf/1810.09026.pdf)
  - Learning Temporal Point Processes via Reinforcement Learning. [paper](https://arxiv.org/pdf/1811.05016.pdf)
  - Memory Augmented Policy Optimization for Program Synthesis and Semantic Parsing. [paper](https://arxiv.org/pdf/1807.02322.pdf) [code](https://github.com/crazydonkey200/neural-symbolic-machines)
#### Hierarchical
  - Flexible Neural Representation for Physics Prediction. [paper](https://arxiv.org/pdf/1806.08047.pdf)
  - Data-Efficient Hierarchical Reinforcement Learning. [paper](https://arxiv.org/pdf/1805.08296.pdf)
  - Learning Abstract Options. [paper](https://arxiv.org/pdf/1810.11583.pdf)
#### Intergrating learning and planing
  - Dual Policy Iteration. [paper](https://arxiv.org/pdf/1805.10755.pdf)
  - differentiable mpc for end-to-end planning and control. [paper](https://arxiv.org/pdf/1810.13400.pdf)
  - Learning Plannable Representations with Causal InfoGAN. [paper](https://arxiv.org/pdf/1807.09341.pdf)
#### Imitation rl
  - Multi-Agent Generative Adversarial Imitation Learning. [paper](https://papers.nips.cc/paper/7975-multi-agent-generative-adversarial-imitation-learning.pdf)
#### Inverse reinforcement learning
  - an event-based framework for task specification and control. [paper](https://arxiv.org/pdf/1805.11686.pdf)
#### exploration
  - Context-Dependent Upper-Confidence Bounds for Directed Exploration. [paper](https://arxiv.org/pdf/1811.06629.pdf)
  - Playing hard exploration games by watching YouTube. [paper](https://arxiv.org/pdf/1805.11592.pdf)
#### CV related
  - Unsupervised Video Object Segmentation for Deep Reinforcement Learning. [paper](https://arxiv.org/pdf/1805.07780.pdf)
  - Hybrid Retrieval-Generation Reinforced Agent for Medical Image Report Generation. [paper](https://arxiv.org/pdf/1805.08298.pdf)
  - Visual Reinforcement Learning with Imagined Goals. [paper](https://arxiv.org/pdf/1807.04742.pdf)
  - Neural-Symbolic VQA: Disentangling Reasoning from Vision and Language Understanding. [paper](https://papers.nips.cc/paper/7381-neural-symbolic-vqa-disentangling-reasoning-from-vision-and-language-understanding.pdf)
#### meta-learning
  - Meta-Reinforcement Learning of Structured Exploration Strategies. [paper](https://arxiv.org/pdf/1802.07245.pdf)
  - Evolved Policy Gradients. [paper](https://arxiv.org/pdf/1802.04821.pdf)
  - Neural Arithmetic Logic Units. [paper](https://arxiv.org/pdf/1808.00508.pdf)
  - Meta-Learning MCMC Proposals. [paper](https://papers.nips.cc/paper/7669-meta-learning-mcmc-proposals.pdf)
  - Probabilistic Model-Agnostic Meta-Learning. [paper](https://arxiv.org/pdf/1806.02817.pdf)
  - Meta-Gradient Reinforcement Learning. [paper](https://papers.nips.cc/paper/7507-meta-gradient-reinforcement-learning.pdf)
#### Generative Models
  - Deep Generative Models with Learnable Knowledge Constraints. [paper](https://arxiv.org/pdf/1806.09764.pdf)
  - Are GANs Created Equal? A Large-Scale Study. [paper](https://arxiv.org/pdf/1711.10337.pdf)
#### safe
  - Learning Safe Policies with Expert Guidance. [paper](https://arxiv.org/pdf/1805.08313.pdf)
  - Adversarial Attacks on Stochastic Bandits. [paper](https://arxiv.org/pdf/1810.12188.pdf)
#### multitask
  - Multi-Task Learning as Multi-Objective Optimization. [paper](https://arxiv.org/pdf/1810.04650.pdf)
  - Learning to Multitask. [paper](https://papers.nips.cc/paper/7819-learning-to-multitask.pdf)
#### Interpretability
  - Human-in-the-Loop Interpretability Prior. [paper](https://arxiv.org/pdf/1805.11571.pdf)
  - Towards Robust Interpretability with Self-Explaining Neural Networks. [paper](https://arxiv.org/abs/1806.07538)
#### undeterminded
  - end-to-end differentiable physics for learning and control. [paper](https://papers.nips.cc/paper/7948-end-to-end-differentiable-physics-for-learning-and-control.pdf) [code](https://github.com/locuslab/lcp-physics)
  - Recurrent World Models Facilitate Policy Evolution. [paper](https://arxiv.org/pdf/1809.01999.pdf)
  - Learning to Play with Intrinsically-Motivated Self-Aware Agents. [paper](https://arxiv.org/pdf/1802.07442.pdf)
  - Reward learning from human preferences and demonstrations in Atari. [paper](https://arxiv.org/pdf/1811.06521.pdf)
  - On Learning Intrinsic Rewards for Policy Gradient Methods. [paper](https://papers.nips.cc/paper/7715-on-learning-intrinsic-rewards-for-policy-gradient-methods.pdf)
  - DeepProbLog: Neural Probabilistic Logic Programming. [paper](https://arxiv.org/pdf/1805.10872.pdf)
  - Scalable End-to-End Autonomous Vehicle Testing via Rare-event Simulation. [paper](https://arxiv.org/pdf/1811.00145.pdf)
  - Relational recurrent neural networks. [paper](https://arxiv.org/pdf/1806.01822.pdf) [code](https://github.com/L0SG/relational-rnn-pytorch)
  - How Does Batch Normalization Help Optimization? [paper](https://arxiv.org/pdf/1805.11604.pdf)
  - Randomized Prior Functions for Deep Reinforcement Learning. [paper](https://arxiv.org/pdf/1806.03335.pdf)
  - Transfer Learning with Neural AutoML. [paper](https://papers.nips.cc/paper/8056-transfer-learning-with-neural-automl.pdf)
  - Neural Guided Constraint Logic Programming for Program Synthesis. [paper](http://www.cs.toronto.edu/~zemel/documents/zhangNeuralConstraintProg.pdf) [code](https://github.com/xuexue/neuralkanren)
