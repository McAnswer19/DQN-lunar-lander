# DQN_lunar_lander


![alt text](https://github.com/McAnswer19/DQN_lunar_lander/blob/master/lunar_lander.jpg)


A deep Q-learning project on the OpenAI LunarLander problem (https://gym.openai.com/envs/LunarLander-v2/) that I wrote as part of group project. deep Q-learning networks (DQN) is a form of deep reinforcement learning where an agent uses a neural network to approximate Q-learning in very high-dimensional spaces. For any finite Markov decision process (FMDP), Q-learning will find the optimal behavior, though in practice its applications are more limited. For the lunar lander problem implementation, the agent achieves perfect play after about 400 episodes (about one hour of training on an NVIDIA P1000 Quadro). 

This project was an incredible amount of fun, and I got along really well with my my teammates. The final network had a topology of 324 neurons and over 2.1 million connections with two hidden layers, ReLu activation, and Adam optimization. The DQN also made use of an extremely large replay buffer (over 500,000 state-action transitions) and a target network that used hard-tau updates every 600th step along with annealed exploration.  

Please note that that the jupyter notebook files might be slightly messy, as they were taken from another repo that was deleted. Also note that V7 was meant for producing the final video output for the project and includes code that is incompatible with Windows. V6 should be fully compatible with Windows, and should be nearly identical in terms of agent performance. Earlier version are included to show the progression of the project. 




