# Awesome Deep RL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome Deep Reinforcement Learning resources.

## Contents

- [Libraries](#libraries)
- [Benchmarks](#benchmarks)
- [Environments](#environments)
- [Competitions](#competitions)
- [Timeline](#timeline)
- [Books](#books)
- [Tutorials](#tutorials)
- [Blog](#blogs)

## Libraries

- [Berkeley Ray RLLib](https://github.com/ray-project/ray) - An open-source library for reinforcement learning that offers both high scalability and a unified API for a variety of applications.
- [Berkeley Softlearning](https://github.com/rail-berkeley/softlearning) - A reinforcement learning framework for training maximum entropy policies in continuous domains.
- [ChainerRL](https://github.com/chainer/chainerrl) - A deep reinforcement learning library built on top of Chainer.
- [DeepMind OpenSpiel](https://github.com/deepmind/open_spiel) - A collection of environments and algorithms for research in general reinforcement learning and search/planning in games.
- [DeepMind TRFL](https://github.com/deepmind/trfl) - TensorFlow Reinforcement Learning.
- [DeepRL](https://github.com/ShangtongZhang/DeepRL) - Modularized Implementation of Deep RL Algorithms in PyTorch.
- [Facebook ELF](https://github.com/pytorch/ELF) - A platform for game research with AlphaGoZero/AlphaZero reimplementation.
- [Facebook Horizon](https://github.com/facebookresearch/Horizon) - A platform for Applied Reinforcement Learning.
- [garage](https://github.com/rlworkgroup/garage) - A toolkit for reproducible reinforcement learning research.
- [Google Dopamine](https://github.com/google/dopamine) - A research framework for fast prototyping of reinforcement learning algorithms.
- [Google TF-Agents](https://github.com/tensorflow/agents) - TF-Agents is a library for Reinforcement Learning in TensorFlow.
- [MAgent](https://github.com/geek-ai/MAgent) - A Platform for Many-agent Reinforcement Learning.
- [NervanaSystems coach](https://github.com/NervanaSystems/coach) - Reinforcement Learning Coach by Intel AI Lab.
- [OpenAI Baselines](https://github.com/openai/baselines) - High-quality implementations of reinforcement learning algorithms.
- [pytorch-a2c-ppo-acktr-gail](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr-gail) - PyTorch implementation of Advantage Actor Critic (A2C), Proximal Policy Optimization (PPO), Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation (ACKTR) and Generative Adversarial Imitation Learning (GAIL).
- [pytorch-rl](https://github.com/navneet-nmk/pytorch-rl) - Model-free deep reinforcement learning algorithms implemented in Pytorch.
- [RLgraph](https://github.com/rlgraph/rlgraph) - Modular computation graphs for deep reinforcement learning.
- [RLkit](https://github.com/vitchyr/rlkit) - Reinforcement learning framework and algorithms implemented in PyTorch.
- [SLM Lab](https://github.com/kengz/SLM-Lab) - Modular Deep Reinforcement Learning framework in PyTorch.
- [Stable Baselines](https://github.com/hill-a/stable-baselines) - A fork of OpenAI Baselines, implementations of reinforcement learning algorithms.
- [TensorForce](https://github.com/tensorforce/tensorforce) - A TensorFlow library for applied reinforcement learning.
- [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents) - Unity Machine Learning Agents Toolkit.
- [vel](https://github.com/MillionIntegrals/vel) - Bring velocity to deep-learning research.
- [reaver](https://github.com/inoryy/reaver) - A modular deep reinforcement learning framework with a focus on various StarCraft II based tasks.

## Benchmarks

- [DeepMind bsuite](https://github.com/deepmind/bsuite/tree/master/bsuite)
- [OpenAI baselines-results](https://github.com/openai/baselines-results)
- [OpenAI Baselines](https://github.com/openai/baselines#benchmarks)
- [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/spinningup/bench.html)
- [ray rl-experiments](https://github.com/ray-project/rl-experiments)
- [rl-baselines-zoo](https://github.com/araffin/rl-baselines-zoo/blob/master/benchmark.md)
- [SLM Lab](https://github.com/kengz/SLM-Lab/blob/master/BENCHMARK.md)
- [vel](https://blog.millionintegrals.com/vel-pytorch-meets-baselines)
- [yarlp](https://github.com/btaba/yarlp)

## Environments

- [AI2-THOR](https://github.com/allenai/ai2thor) - A near photo-realistic interactable framework for AI agents.
- [Animal-AI Olympics](https://github.com/beyretb/AnimalAI-Olympics) - An AI competition with tests inspired by animal cognition.
- [Berkeley rl-generalization](https://github.com/sunblaze-ucb/rl-generalization) - Modifiable OpenAI Gym environments for studying generalization in RL.
- [BTGym](https://github.com/Kismuz/btgym) - Scalable event-driven RL-friendly backtesting library. Build on top of Backtrader with OpenAI Gym environment API.
- [Carla](https://github.com/carla-simulator/carla) - Open-source simulator for autonomous driving research.
- [CuLE](https://github.com/NVlabs/cule) - A CUDA port of the Atari Learning Environment (ALE).
- [Deepdrive](https://github.com/deepdrive/deepdrive) - End-to-end simulation for self-driving cars.
- [DeepMind DM Control](https://github.com/deepmind/dm_control) - The DeepMind Control Suite and Package.
- [DeepMind Lab](https://github.com/deepmind/lab) - A customisable 3D platform for agent-based AI research.
- [DeepMind pycolab](https://github.com/deepmind/pycolab) - A highly-customisable gridworld game engine with some batteries included.
- [DeepMind PySC2](https://github.com/deepmind/pysc2) - StarCraft II Learning Environment.
- [Facebook EmbodiedQA](https://github.com/facebookresearch/EmbodiedQA) - Train embodied agents that can answer questions in environments.
- [Facebook Habitat](https://github.com/facebookresearch/habitat-api) - A modular high-level library to train embodied AI agents across a variety of tasks, environments, and simulators.
- [Facebook House3D](https://github.com/facebookresearch/House3D) - A Rich and Realistic 3D Environment.
- [Facebook natural_rl_environment](https://github.com/facebookresearch/natural_rl_environment) - natural signal Atari environments, introduced in the paper Natural Environment Benchmarks for Reinforcement Learning.
- [Google Research Football](https://github.com/google-research/football) - An RL environment based on open-source game Gameplay Football.
- [GVGAI Gym](https://github.com/rubenrtorrado/GVGAI_GYM) - An OpenAI Gym environment for games written in the Video Game Description Language, including the Generic Video Game Competition framework.
- [gym-doom](https://github.com/ppaquette/gym-doom) - Doom environments based on VizDoom.
- [gym-duckietown](https://github.com/duckietown/gym-duckietown) - Self-driving car simulator for the Duckietown universe.
- [gym-gazebo2](https://github.com/AcutronicRobotics/gym-gazebo2) - A toolkit for developing and comparing reinforcement learning algorithms using ROS 2 and Gazebo.
- [gym-ignition](https://github.com/robotology/gym-ignition) - Experimental OpenAI Gym environments implemented with Ignition Robotics.
- [gym-super-mario](https://github.com/ppaquette/gym-super-mario) - 32 levels of original Super Mario Bros.
- [Holodeck](https://github.com/BYU-PCCL/holodeck) - High Fidelity Simulator for Reinforcement Learning and Robotics Research.
- [home-platform](https://github.com/HoME-Platform/home-platform) - A platform for artificial agents to learn from vision, audio, semantics, physics, and interaction with objects and other agents, all within a realistic context
- [ma-gym](https://github.com/koulanurag/ma-gym) - A collection of multi agent environments based on OpenAI gym.
- [mazelab](https://github.com/zuoxingdong/mazelab) - A customizable framework to create maze and gridworld environments.
- [Microsoft AirSim](https://github.com/Microsoft/AirSim) - Open source simulator for autonomous vehicles built on Unreal Engine / Unity, from Microsoft AI & Research.
- [Microsoft Jericho](https://github.com/microsoft/jericho) - A learning environment for man-made Interactive Fiction games.
- [Microsoft Malmö](https://github.com/Microsoft/malmo) - A platform for Artificial Intelligence experimentation and research built on top of Minecraft.
- [Microsoft MazeExplorer](https://github.com/microsoft/MazeExplorer) - Customisable 3D environment for assessing generalisation in Reinforcement Learning.
- [Microsoft TextWorld](https://github.com/microsoft/TextWorld) - A text-based game generator and extensible sandbox learning environment for training and testing reinforcement learning (RL) agents.
- [MineRL](https://github.com/minerllabs/minerl) - MineRL Competition for Sample Efficient Reinforcement Learning.
- [MuJoCo](http://www.mujoco.org) - Advanced physics simulation.
- [OpenAI Coinrun](https://github.com/openai/coinrun) - Code for the environments used in the paper Quantifying Generalization in Reinforcement Learning.
- [OpenAI Gym Retro](https://github.com/openai/retro) - Retro Games in Gym.
- [OpenAI Gym Soccer](https://github.com/openai/gym-soccer) - A multiagent domain featuring continuous state and action spaces.
- [OpenAI Gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms.
- [OpenAI Multi-Agent Particle Environment](https://github.com/openai/multiagent-particle-envs) - A simple multi-agent particle world with a continuous observation and discrete action space, along with some basic simulated physics.
- [OpenAI Neural MMO](https://github.com/openai/neural-mmo) - A Massively Multiagent Game Environment.
- [OpenAI Roboschool](https://github.com/openai/roboschool) - Open-source software for robot simulation, integrated with OpenAI Gym.
- [OpenAI RoboSumo](https://github.com/openai/robosumo) - A set of competitive multi-agent environments used in the paper Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environments.
- [Personae](https://github.com/Ceruleanacg/Personae) - RL & SL Methods and Envs For Quantitative Trading.
- [Pommerman](https://github.com/MultiAgentLearning/playground) - A clone of Bomberman built for AI research.
- [pybullet-gym](https://github.com/benelot/pybullet-gym) - Open-source implementations of OpenAI Gym MuJoCo environments for use with the OpenAI Gym Reinforcement Learning Research Platform
- [PyGame Learning Environment](https://github.com/ntasfi/PyGame-Learning-Environment) - Reinforcement Learning Environment in Python.
- [RLTrader](https://github.com/notadamking/RLTrader) - A cryptocurrency trading environment using deep reinforcement learning and OpenAI's gym.
- [rocket-lander](https://github.com/arex18/rocket-lander) - SpaceX Falcon 9 Box2D continuous-action simulation with traditional and AI controllers.
- [Stanford Gibson Environments](https://github.com/StanfordVL/GibsonEnv) - Real-World Perception for Embodied Agents.
- [Stanford osim-rl](https://github.com/stanfordnmbl/osim-rl) - Reinforcement learning environments with musculoskeletal models.
- [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents) - Unity Machine Learning Agents Toolkit.
- [UnityObstableTower](https://github.com/Unity-Technologies/obstacle-tower-env) - A procedurally generated environment consisting of multiple floors to be solved by a learning agent.
- [VizDoom](https://github.com/mwydmuch/ViZDoom) - Doom-based AI Research Platform for Reinforcement Learning from Raw Visual Information.

## Competitions

- [AWS DeepRacer League 2019](https://aws.amazon.com/deepracer/league/)
- [Flatland Challenge 2019](https://www.aicrowd.com/challenges/flatland-challenge)
- [NeurIPS 2019: Animal-AI Olympics](http://animalaiolympics.com/)
- [NeurIPS 2019: Game of Drones](https://www.microsoft.com/en-us/research/academic-program/game-of-drones-competition-at-neurips-2019/)
- [NeurIPS 2019: Learn to Move - Walk Around](https://www.aicrowd.com/challenges/neurips-2019-learning-to-move-walk-around)
- [NeurIPS 2019: MineRL Competition](http://minerl.io/competition/)
- [NeurIPS 2019: Reconnaissance Blind Chess](https://rbc.jhuapl.edu/)
- [NeurIPS 2019: Robot open-Ended Autonomous Learning](https://www.aicrowd.com/challenges/robot-open-ended-autonomous-learning-real)
- [Unity Obstacle Tower Challenge 2019](https://blogs.unity3d.com/2019/01/28/obstacle-tower-challenge-test-the-limits-of-intelligence-systems/)

## Timeline

- 1947: [Monte Carlo Sampling](http://eniacinaction.com/the-articles/3-los-alamos-bets-on-eniac-nuclear-monte-carlo-simulations-1947-8/)
- 1958: [Perceptron](https://www.ling.upenn.edu/courses/cogs501/Rosenblatt1958.pdf)
- 1959: [Temporal Difference Learning](https://dl.acm.org/citation.cfm?id=1661924)
- 1983: [ASE-ALE — the first Actor-Critic algorithm](https://psycnet.apa.org/record/1984-13799-001)
- 1986: [Backpropagation algorithm](https://www.nature.com/articles/323533a0)
- 1989: [CNNs](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.476.479&rep=rep1&type=pdf)
- 1989: [Q-Learning](http://www.cs.rhul.ac.uk/~chrisw/new_thesis.pdf)
- 1991: [TD-Gammon](http://bkgm.com/books/Robertie-LearningFromTheMachine.html)
- 1992: [REINFORCE](https://dl.acm.org/citation.cfm?id=139614)
- 1992: [Experience Replay](https://dl.acm.org/citation.cfm?id=139620)
- 1994: [SARSA](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.17.2539)
- 1999: [Nvidia invented the GPU](https://www.nvidia.com/object/gpu.html)
- 2007: [CUDA released](https://developer.nvidia.com/cuda-zone)
- 2012: [Arcade Learning Environment (ALE)](https://arxiv.org/abs/1207.4708)
- 2013: [DQN](https://arxiv.org/abs/1312.5602)
- 2015 Feb: [DQN human-level control in Atari](https://www.nature.com/articles/nature14236)
- 2015 Feb: [TRPO](https://arxiv.org/abs/1502.05477)
- 2015 Jun: [Generalized Advantage Estimation](https://arxiv.org/abs/1506.02438)
- 2015 Sep: [Deep Deterministic Policy Gradient (DDPG)](https://arxiv.org/abs/1509.02971)
- 2015 Sep: [DoubleDQN](https://arxiv.org/abs/1509.06461)
- 2015 Nov: [DuelingDQN](https://arxiv.org/abs/1511.06581)
- 2015 Nov: [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)
- 2015 Nov: [TensorFlow](https://www.tensorflow.org/)
- 2016 Feb: [A3C](https://arxiv.org/abs/1602.01783)
- 2016 Mar: [AlphaGo beats Lee Sedol 4-1](https://deepmind.com/alphago-korea)
- 2016 Jun: [OpenAI Gym](https://github.com/openai/gym)
- 2016 Jun: [Generative Adversarial Imitation Learning (GAIL)](https://arxiv.org/abs/1606.03476)
- 2016 Oct: [PyTorch](https://pytorch.org/)
- 2017 Mar: [Model-Agnostic Meta-Learning (MAML)](https://arxiv.org/abs/1703.03400)
- 2017 Jul: [Distributional RL](https://arxiv.org/abs/1707.06887)
- 2017 Jul: [PPO](https://arxiv.org/abs/1707.06347)
- 2017 Aug: [OpenAI DotA 2 1:1](https://openai.com/blog/more-on-dota-2/)
- 2017 Aug: [Intrinsic Cusiority Module (ICM)](https://arxiv.org/abs/1705.05363)
- 2017 Oct: [Rainbow](https://arxiv.org/abs/1710.02298)
- 2017 Dec: [AlphaZero](https://arxiv.org/abs/1712.01815)
- 2018 Jan: [Soft Actor-Critic](https://ai.googleblog.com/2019/01/soft-actor-critic-deep-reinforcement.html)
- 2018 Feb: [IMPALA](https://deepmind.com/blog/article/impala-scalable-distributed-deeprl-dmlab-30)
- 2018 Jun: [Qt-Opt](https://ai.googleblog.com/2018/06/scalable-deep-reinforcement-learning.html)
- 2018 Nov: [Go-Explore solved Montezuma’s Revenge](https://eng.uber.com/go-explore/)
- 2018 Dec: [AlphaZero becomes the strongest player in history for chess, Go, and Shogi](https://deepmind.com/blog/article/alphazero-shedding-new-light-grand-games-chess-shogi-and-go)
- 2018 Dec: [AlphaStar](https://deepmind.com/blog/article/alphastar-mastering-real-time-strategy-game-starcraft-ii)
- 2019 Apr: [OpenAI Five defeated world champions at DotA 2](https://openai.com/five/)
- 2019 May: [FTW Quake III Arena Capture the Flag](https://deepmind.com/blog/article/capture-the-flag-science)

## Books

- [An Introduction to Deep Reinforcement Learning. *Vincent Francois-Lavet, Peter Henderson, Riashat Islam.*](https://www.amazon.com/Introduction-Reinforcement-Learning-Foundations-Machine/dp/1680835386)
- [Reinforcement Learning: An Introduction. *Sutton & Barto.*](https://www.amazon.com/dp/0262039249/ref=cm_sw_r_tw_dp_U_x_t0kwDb34GTGSJ)

## Tutorials

- [Andrew Karpathy Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/)
- [Arthur Juliani Simple Reinforcement Learning in Tensorflow Series](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0)
- [David Silver UCL Course on RL 2015](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
- [Deep RL Bootcamp 2017](https://sites.google.com/view/deep-rl-bootcamp/lectures)
- [DeepMind UCL Deep RL Course 2018](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs)
- [dennybritz/reinforcement-learning](https://github.com/dennybritz/reinforcement-learning)
- [higgsfield/RL-Adventure-2](https://github.com/higgsfield/RL-Adventure-2)
- [higgsfield/RL-Adventure](https://github.com/higgsfield/RL-Adventure)
- [MorvanZhou/Reinforcement Learning Methods and Tutorials](https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow)
- [OpenAI Spinning Up](https://github.com/openai/spinningup)
- [Sergey Levine CS294 Deep Reinforcement Learning Fall 2017](http://rail.eecs.berkeley.edu/deeprlcourse-fa17/index.html)

## Blogs

- [Alex Irpan](https://www.alexirpan.com)
- [Andrew Karpathy](http://karpathy.github.io/)
- [Berkeley AI Research](https://bair.berkeley.edu/blog/)
- [Chris Olah](https://colah.github.io/)
- [David Ha](http://blog.otoro.net/)
- [DeepMind](https://deepmind.com/blog)
- [Distill](https://distill.pub)
- [Facebook AI](https://ai.facebook.com/blog/)
- [Google AI](https://ai.googleblog.com/)
- [Matthew Rahtz](http://amid.fish/)
- [OpenAI](https://openai.com/blog/)
- [The Gradient](https://thegradient.pub/)
- [Uber AI](https://eng.uber.com/category/articles/ai/)
