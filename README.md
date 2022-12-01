# Trusted-RL-for-Autonomous-Driving








The repository is for Safe Reinforcement Learning (RL) research, in which we investigate various safe RL baselines and safe RL benchmarks, including single agent RL and multi-agent RL. If any authors do not want their paper to be listed here, please feel free to contact <gshangd[AT]foxmail.com>. (This repository is under actively development. We appreciate any constructive comments and suggestions)


You are more than welcome to update this list! If you find a paper about Safe RL which is not listed here, please

- fork this repository, add it and merge back;
- or report an issue here;
- or email <gshangd[AT]foxmail.com>.

***
The README is organized as follows:
- [1. Environments Supported](#1-environments-supported)
  * [1.1. Safe Single Agent RL benchmarks](#11-safe-single-agent-rl-benchmarks)
  * [1.2. Safe Multi-Agent RL benchmarks](#12-safe-multi-agent-rl-benchmarks)
- [2. Safe RL Baselines](#2-safe-rl-baselines)
  * [2.1. Safe Single Agent RL Baselines](#21-safe-single-agent-rl-baselines)
  * [2.2. Safe Multi-Agent RL Baselines](#22-safe-multi-agent-rl-baselines)
- [3. Surveys](#3-surveys)
- [4. Thesis](#4-thesis)
- [5. Book](#5-book)

***



### 1. Environments Supported
#### 1.1. Safe Single Agent RL benchmarks
- [AI Safety Gridworlds](https://github.com/deepmind/ai-safety-gridworlds)
- [Safety-Gym](https://github.com/openai/safety-gym)

#### 1.2. Safe Multi-Agent RL benchmarks
- [Safe Multi-Agent Mujoco](https://github.com/chauncygu/Safe-Multi-Agent-Mujoco)
- [Safe Multi-Agent Isaac Gym](https://github.com/chauncygu/Safe-Multi-Agent-Isaac-Gym)
- [Safe Multi-Agent Robosuite](https://github.com/chauncygu/Safe-Multi-Agent-Robosuite)



### 2. Safe RL Baselines

#### 2.1. Safe Single Agent RL Baselines

- High-Confidence Off-Policy Evaluation, [Paper](https://www.ics.uci.edu/~dechter/courses/ics-295/winter-2018/papers/2015Thomas2015.pdf), [Code](https://github.com/chauncygu/Safe-Reinforcement-Learning-Baseline/tree/main/Safe-RL/safeRL) (Accepted by AAAI 2015)

#### 2.2. Uncertainty in RL

- Robust Multi-Agent Reinforcement Learning with Model Uncertainty, [Paper](https://proceedings.neurips.cc/paper/2020/file/774412967f19ea61d448977ad9749078-Paper.pdf), Not Find Code (Accepted by NeurIPS 2020)

- Towards Safe Reinforcement Learning via Constraining Conditional Value-at-Risk, [Paper](https://arxiv.org/pdf/2206.04436.pdf), Not Find Code (Arxiv, 2022)

- Safe, Multi-Agent, Reinforcement Learning for Autonomous Driving, [Paper](https://arxiv.org/pdf/1610.03295.pdf), Not Find Code (Arxiv, Citation 300+, 2016)

- Motion Planning for Autonomous Vehicles in the Presence of Uncertainty Using Reinforcement Learning, [Paper]([https://arxiv.org/pdf/2110.00640v1.pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9636480)), Not Find Code (Accepted by IEEE International Workshop on Intelligent Robots and Systems, 2021)

- Reachability-based Trajectory Safeguard (RTS): A Safe and Fast Reinforcement Learning Safety Layer for Continuous Control, [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9369910), Not Find Code (Accepted by IEEE RAL, 2021)

- A Safety Aware Model-Based Reinforcement Learning Framework for Systems with Uncertainties, [Paper](https://scc-lab.github.io/Preprints/SCC.Mahmud.Hareland.ea2021.pdf), Not Find Code (Accepted by American Control Conference, 2021)

- Constrained Reinforcement Learning for Dynamic Optimization under Uncertainty, [Paper](https://www.sciencedirect.com/science/article/pii/S2405896320306455), Not Find Code (Accepted by IFAC, 2020)

- Benchmarking Safe Deep Reinforcement Learning in Aquatic Navigation, [Paper](https://arxiv.org/pdf/2110.00640v1.pdf), Not Find Code (Accepted by IROS, 2021)

- Safe Reinforcement Learning with Model Uncertainty Estimates, [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8793611), Not Find Code (Accepted by IEEE International Conference on Robotics and Automation, 2019)

- Uncertainty-aware Contact-safe Model-based Reinforcement Learning, [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9376242), Not Find Code (Accepted by IEEE RAL, 2021)

- Uncertainty-Aware Reinforcement Learning for Collision Avoidance, [Paper](https://arxiv.org/pdf/1702.01182.pdf), Not Find Code (Arxiv, 2017)

- Lyapunov-based uncertainty-aware safe reinforcement learning, [Paper](https://arxiv.org/ftp/arxiv/papers/2107/2107.13944.pdf), Not Find Code (Arxiv, 2021)

- Reinforcement Learning with Uncertainty Estimation for Tactical Decision-Making in Intersections, [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9294407), Not Find Code (Accepted by IEEE International Conference on Intelligent Transportation Systems, 2020)

- Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor, [Paper](https://proceedings.mlr.press/v80/haarnoja18b.html), [Code](https://github.com/haarnoja/sac) (Accepted by International Conference on Machine Learning, 2018)

- Reinforcement Learning Under Moral Uncertainty, [Paper](https://proceedings.mlr.press/v139/ecoffet21a.html), [Code](https://github.com/uber-research/normative-uncertainty) (Accepted by International Conference on Machine Learning, 2021)

- Distributional Reinforcement Learning with Quantile Regression, [Paper](https://arxiv.org/pdf/1710.10044.pdf), Not Find Code (Arxiv, 2019)

- Estimating Risk and Uncertainty in Deep Reinforcement Learning, [Paper](https://arxiv.org/abs/1905.09638), [Code](https://github.com/IndustAI/risk-and-uncertainty) (Accepted by ICML, 2020)

- Reinforcement Learning for Safety-Critical Control under Model Uncertainty, using Control Lyapunov Functions and Control Barrier Functions, [Paper](https://arxiv.org/pdf/2004.07584.pdf), Not Find Code (Arxiv, 2020)

- Automated Lane Change Decision Making using Deep Reinforcement Learning in Dynamic and Uncertain Highway Environment, [Paper](https://ieeexplore.ieee.org/document/8917192), Not Find Code (Accepted by IEEE Intelligent Transportation Systems Conference, 2019)

- Online Robust Reinforcement Learning with Model Uncertainty, [Paper](https://proceedings.neurips.cc/paper/2021/hash/3a4496776767aaa99f9804d0905fe584-Abstract.html), Not Find Code (Accepted by Advances in Neural Information Processing Systems)

- Uncertainty-driven Imagination for Continuous Deep Reinforcement Learning, [Paper](https://proceedings.mlr.press/v78/kalweit17a.html), (Accepted by Conference on Robot Learning)


#### 2.3. Generalization in RL

- Zero-Shot Task Generalization with Multi-Task Deep Reinforcement Learning, [Paper](http://proceedings.mlr.press/v70/oh17a/oh17a.pdf), Not Find Code (Accepted by International Conference on Machine Learning, 2017)

- Quantifying Generalization in Reinforcement Learning, [Paper](https://proceedings.mlr.press/v97/cobbe19a.html), [Code](https://github.com/openai/coinrun) (Accepted by International Conference on Machine Learning, 2019)

- NETWORK RANDOMIZATION: A SIMPLE TECHNIQUE FOR GENERALIZATION IN DEEP REINFORCEMENT LEARNING, [Paper](http://arxiv.org/abs/1910.05396), [Code](https://github.com/pokaxpoka/netrand) (Accepted by ICLR, 2020)

- Invariant Policy Optimization: Towards Stronger Generalization in Reinforcement Learning, [Paper](http://proceedings.mlr.press/v144/sonar21a/sonar21a.pdf), [Code](https://github.com/irom-lab/Invariant-Policy-Optimization) (Accepted by Learning for Dynamics and Control, 2021)

- Improving Generalization in Reinforcement Learning with Mixture Regularization, [Paper](https://proceedings.neurips.cc/paper/2020/file/5a751d6a0b6ef05cfe51b86e5d1458e6-Paper.pdf), [Code](https://github.com/kaixin96/mixreg) (Accepted by Neural Information Processing Systems, 2020)

- High Confidence Generalization for Reinforcement Learning, [Paper](http://proceedings.mlr.press/v139/kostas21a/kostas21a.pdf), Not Find Code (Accepted by International Conference on Machine Learning, 2021)

- Generalization of Reinforcement Learning with Policy-Aware Adversarial Data Augmentation, [Paper](https://arxiv.org/pdf/2106.15587.pdf), Not Find Code (Arxiv, 2021)

- Generalization in Reinforcement Learning: Safely Approximating the Value Function, [Paper](https://proceedings.neurips.cc/paper/1994/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), Not Find Code (Accepted by Advances in Neural Information Processing Systems(NIPS), 1994)

- Generalization in Reinforcement Learning with Selective Noise Injection and Information Bottleneck, [Paper](https://proceedings.neurips.cc/paper/2019/hash/e2ccf95a7f2e1878fcafc8376649b6e8-Abstract.html), [Code](https://github.com/microsoft/IBAC-SNI/) (Accepted by NeurIPS, 2019)

- Generalization in Reinforcement Learning by Soft Data Augmentation, [Paper](https://ieeexplore.ieee.org/document/9561103/), [Code](https://github.com/nicklashansen/dmcontrol-generalization-benchmark) (Accepted by IEEE International Conference on Robotics and Automation (ICRA), 2021)

- Generalization and Regularization in DQN, [Paper](http://arxiv.org/abs/1810.00123), Not Find Code (Arxiv, 2020)

- Dynamics Generalization via Information Bottleneck in Deep Reinforcement Learning, [Paper](https://arxiv.org/pdf/2008.00614.pdf), Not Find Code (Arxiv, 2020)

- Domain Randomization for Transferring Deep Neural Networks from Simulation to the Real World, [Paper](https://ieeexplore.ieee.org/abstract/document/8202133), Not Find Code (Accepted by IEEE International Conference on Intelligent Robots and Systems (IROS), 2017)

- Active Domain Randomization, [Paper](https://proceedings.mlr.press/v100/mehta20a.html), Not Find Code (Accepted by Conference on Robot Learning, 2020)
