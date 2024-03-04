# Deep-learning
通过课程学习了有监督学习和无监督学习的深度学习，为了满足好奇，自学了强化学习的相关知识，做了AI玩Mario的一个小项目。介绍了强化学习中Agent, Environment, State, action, policy function π(a|s)的概念；通过OpenAI-Gym这个工具包引入并初始化了环境，并对环境进行了灰度处理、矢量化处理和4帧堆叠的环境预处理。调用Stable-baselines3库，采用PPO算法的CnnPolicy的网络进行学习，每隔50000次保存一次模型，共跑了5M次，最终得到较好的训练结果。

效果展示:
