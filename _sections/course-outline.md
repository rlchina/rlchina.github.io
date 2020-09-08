--- 
title: 课程内容 
icon: fa-th 
order: 4 
---
<p style="text-align:justify; text-justify:inter-ideograph;color: black">

0、汪军: Openning and Introduction <br />
<br />
1、卢宗青: Introduction to Reinforcement Learning and Value-based Methods <br />
<b>- Introduction to Reinforcement Learning </b><br />
<b>    &emsp; - About RL </b><br />
<b>    &emsp; - RL problem </b><br />
<b>    &emsp; - Markov Decision Processes </b><br />
<b>- Value-based Methods </b><br />
<b>    &emsp; - Dynamic Programming </b><br />
<b>    &emsp; - Monte Carlo </b><br />
<b>    &emsp; - TD Learning </b><br />
<b>    &emsp; - Off-policy Learning </b><br />
<b>    &emsp; - DQN and its variants </b><br />
<br />
2、汪军: Foundations of Reinforcement Learning <br />
<b>- Recap (yesterday’s lecture) </b><br />
<b>    &emsp; - MDPs </b><br />
<b>    &emsp; - Value iterations and policy iterations </b><br />
<b>    &emsp; - Tabular Q-Learning </b><br />
<b>- Policy approaches </b><br />
<b>    &emsp; - Markov chains </b><br />
<b>    &emsp; - Policy gradient </b><br />
<b>- Computational learning theory </b><br />
<b>    &emsp; - PAC learning concepts </b><br />
<b>    &emsp; - Learning bound for finite H </b><br />
<b>- Theoretical analysis </b><br />
<b>    &emsp; - Approximate dynamic programming </b><br />
<b>    &emsp; - Performance bounds </b><br />
<b>    &emsp; - Sample complexity </b><br />
<br />
3、Haitham: Non-Convex Optimisation: Survey & ADAM's Proof <br />
<b>- Motivation, Functions and Solution Types </b><br />
<b>    &emsp; - Applications of optimisation in Machine Learning </b><br />
<b>    &emsp; - Convex vs Non-Convex Optimisation Techniques </b><br />
<b>    &emsp; - Non-Convex Optimisation Solution Types </b><br />
<b>- Brief Survey and ADAM Optimiser </b><br />
<b>    &emsp; - Zero-Order Techniques </b><br />
<b>    &emsp; - First-Order Techniques </b><br />
<b>    &emsp; - Second-Order Techniques </b><br />
<b>- ADAM’s Proof from NeurIPS 2018 </b><br />
<b>    &emsp; - Proof Strategy </b><br />
<b>    &emsp; - Assumptions </b><br />
<b>    &emsp; - Loss Function Difference Bound and Stationary Point Convergence </b><br />
<br />
4、张伟楠: Model-based Reinforcement Learning <br />
<b>- Introduction to MBRL from Dyna </b><br />
<b>- Shooting methods: RS, PETS, POPLIN </b><br />
<b>- Theoretic bounds and methods: SLBO, MBPO & BMPO </b><br />
<b>- Backpropagation through paths: SVG and MAAC </b><br />
<br />
5、朱占星: Control as Inference  <br />
<b>- Basic of (probabilistic) graphical models (GM) </b><br />
<b>    &emsp; - D-separation </b><br />
<b>    &emsp; - Variational inference </b><br />
<b>- Connection between RL and inference in GM </b><br />
<b>    &emsp; - A graphical model for control as inference </b><br />
<b>- Maximum entropy RL and variational inference  </b><br />
<b>- Soft Q-Learning </b><br />
<b>- Soft Actor-Critic </b><br />
<br />
6、俞扬: Imitation Learning <br />
<b>- Previously </b><br />
<b>- Supervised Learning & Behavior Cloning </b><br />
<b>- Generative Adversarial Learning & GAIL </b><br />
<b>- Advanced Topics </b><br />
<b>- From Imitating Policies to Imitating Environments </b><br />
<br />
7、郝建业: Learning with Sparse Rewards <br />
<b>- From Sparse to Dense </b><br />
<b>    &emsp;- Reward Learning/Shaping </b><br />
<b>    &emsp;- Temporal/spatial credit assignment (single-agent/multiagent settings) </b><br />
<b>    &emsp;- Task hierarchical decomposition (hierarchical RL) </b><br />
<br />
8、张海峰: Game Theory Basics  <br />
<b>- Motivation and Normal-form Game </b><br />
<b>- Extensive-form Game and Imperfect Information </b><br />
<b>- Bayesian Game and Incomplete Information </b><br />
<b>- Nash Equilibrium and Variants </b><br />
<b>- Theoretical Results of Nash Equilibrium </b><br />
<b>- Repeated Game and Learning Methods </b><br />
<b>- Alternate Solution Concepts and Evolutionary Game Theory </b><br />
<br />
9、安波: Multi-agent Systems  <br />
<b>- History and Current Status </b><br />
<b>- Key research areas in MAS </b><br />
<b>- Recent advances </b><br />
<b>    &emsp;- Computer poker </b><br />
<b>    &emsp;- Game theory for security </b><br />
<b>    &emsp;- Multi-agent RL </b><br />
<br />
10、张崇洁: Deep Multi-agent Reinforcement Learning<br />
<b>- Value-Based Methods </b><br />
<b>    &emsp;- Paradigm: Centralized Training and Decentralized Execution </b><br />
<b>    &emsp;- Basic methods: VDN, QMIX, QPLEX </b><br />
<b>    &emsp;- Theoretical analysis </b><br />
<b>    &emsp;- Extensions </b><br />
<b>- Policy Gradient Methods </b><br />
<b>    &emsp;- Paradigm: Centralized Critic and Decentralized Actors </b><br />
<b>    &emsp;- Method: Decomposable Off-Policy Policy Gradient (DOP) </b><br />
<br />
11、杨耀东: Advances of Multi-agent Learning(in Gaming AI) <br />
<b>- Multi-agent Learning for Games </b><br />
<b>    &emsp;- Motivation of studying games </b><br />
<b>    &emsp;- When self-play does not work </b><br />
<b>    &emsp;- The landscape of real-world games </b><br />
<b>    &emsp;- The necessity of studying meta-games </b><br />
<b>- Policy Evaluation in Meta-games </b><br />
<b>    &emsp;- Elo rating </b><br />
<b>    &emsp;- Nash Equilibrium  </b><br />
<b>    &emsp;- Replicator dynamics </b><br />
<b>    &emsp;- α-Rank & α^α-Rank </b><br />
<b>- Policy Improvement in Meta-games </b><br />
<b>    &emsp;- Fictitious play & generalised weaken fictitious play </b><br />
<b>    &emsp;- Double oracle & PSRO </b><br />
<b>    &emsp;- PSRO-Nash, PSRO-Rectified-Nash, α-PSRO </b><br />
<br />
12、徐任远: Mean-field Games and Controls <br />
<b>- General Mean-Field Games (GMFG)  </b><br />
<b>    &emsp; - Motivating Example: Ad Auction  </b><br />
<b>    &emsp; - General N-player Game and GMFG  </b><br />
<b>    &emsp; - Existence and Uniqueness of GMFG Solution  </b><br />
<b>- GMFG with RL  </b><br />
<b>    &emsp; - GMF-Q: Q-learning in GMFG </b><br />
<b>    &emsp; - Convergence and Complexity of RL  </b><br />
<b>- Learning Mean-Field Controls  </b><br />
<b>    &emsp; - From MARL to Mean-field Control (MFC)  </b><br />
<b>- Q-learning Algorithm for MFC   </b><br />
<b>    &emsp; - Algorithm Design  </b><br />
<b>    &emsp; - Convergence and Complexity Results  </b><br />
<br />
13、全体导师: Panel Discussion <br />
<br />
</p>