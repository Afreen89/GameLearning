# GameLearning
The goal is to train Deep Reinforcement Learning (DRL) agents that receive image-inputs from a game simulator, and that output game actions to play the game autonomously. The following simulator will be used to play the game of SuperMarioBros 1-1-v0: https://github.com/Kautenja/gym-super-mario-bros

Evaluated the agents using metrics sush as Avg. Reward, Avg. Q-Value, Avg. Game Score, Avg. Steps Per Episode, and Training and Test Times.

Trained at least three different agents (in addition to any baseline), which can differ in their state representation (CNN, CNN-RNN, CNN-Transformer) and/or different learning algorithms. and reports with three different seeds and average their results.

![1](https://user-images.githubusercontent.com/101992840/216442137-d62da35f-252f-4df4-8507-5985f4b494c6.png)
![2](https://user-images.githubusercontent.com/101992840/216442147-caf3ab75-91ec-452e-b43e-eecdfbc94619.png)
![3](https://user-images.githubusercontent.com/101992840/216442161-cf067e47-baea-4007-b0c2-a4e4d1d2f5cd.png)


Conclusion: 
The results were not as good as expected. One of the reason could be the number of training epochs. It took four hours to train one agent. 
