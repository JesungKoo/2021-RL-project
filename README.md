# 2021-RL-project
2021년도 2학기 강화학습특론 팀프로젝트

제안서 제출본

Title
Agent for Non-competitive game play: Reinforcement Learning for Objective Generation

Members
* Koo Jesung, Department of Electrical and Computer Engineering,  jesungkoo@gmail.com
* Lee Key Heon, Department of Artificial Intelligence

Topic idea

Game environment has been used as a great testbed of reinforcement learning algorithms, due to simple rules and objective. Leveraging Markov Decision Process(MDP) and some deep learning architectures, researchers have reached superhuman performance in famous game environment such as Atari and Go. Not only in full-information environment, but also in some complex games such as Starcraft II and DotA 2, AI agents outperformed top-tier human players.

Most researchers think that those game AIs will eventually lead to general intelligence, due to similarity of game and real world. However, still most of methods rely upon game rules: pre-coded action space, carefully designed reward function, and competitive nature of games. With these premises, it becomes an optimization problem, rather then general intelligence which can adapt or help with real-world problems. Achieving optimiziation can help in manners of training. Especially in Go, after AlphaGo and AlphaZero it became typical for professional players to train themselves with AI agents.

However, it is nothing for someone out of Go. What we really want from general intelligence is reliable prediction, rather than superhuman performance in some sports domains. Therefore, we are trying to build a game playing agent which can understand the environment, set its objectives by itself, and accomplish objectives by itself to achieve final goal that is implicit in non-competitive games known as Role-Playing Games(RPG), Social Networking Game(SNG), and Colectible Card Game(CCG).

References
[1] OpenAI. Dota 2 with Large Scale Deep Reinforcement Learning. arXiv:1912.06680 [cs.LG]
[2] Niels Justesen, Philip Bontrager, Julian Togelius, Sebastian Risi. Deep Learning for Video Game Playing. arXiv:1708.07902 [cs.AI]
[3] Vinyals, O., Babuschkin, I., Czarnecki, W. M., Mathieu, M., Dudzik, A., Chung, J., Choi, D. H., Powell, R., Ewalds, T., Georgiev, P., et al. Grandmaster level in StarCraft II using multi-agent reinforcement learning. Nature, 1–5 (2019).
[4] Carlos Florensa, David Held, Xinyang Geng, Pieter Abbeel. Automatic Goal Generation for Reinforcement Learning Agents. arXiv:1705.06366 [cs.LG]
