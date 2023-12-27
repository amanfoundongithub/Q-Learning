### Reinforcement Learning to Train An Automated Taxi

The algorithm used to train the driver is Q-Learning. The Taxi is taken from OpenAI's Taxi-v3, an open source implementation of the Taxi problem. Hyper parameter tuning will be added later.
For now, the following parameters were used: 
- TD Learning Rate : 0.1
- Discount factor : 0.99

For now, these values were randomly chosen. Using Q learning, the driver was able to learn to drive with minimal loss. Starting from State 123 [Taxi has 500 states], we reached destination in 8 steps, an optimal value.


### Reinforcement Learning to Train A Cart

The algorithm used to train the cart is Q-Learning. The Cart is taken from OpenAI's CartPole, an open source implementation of the Cart Pole problem. Hyper parameter tuning will be added later.
For now, the following parameters were used: 
- TD Learning Rate : 0.1
- Discount factor : 0.99

For now, these values were randomly chosen. Using Q learning, the cart was able to mantain pole for a longer period of time. Initially, the maximum duration was around ~14 but gradually after training on a 1,00,000 episodes, it became ~250 on an average. 

### Reinforcement Learning to Train A Mountain Car

The algorithm used to train the cart is Q-Learning. The Cart is taken from OpenAI's Mountain Car, an open source implementation of the Mountain Car problem. Hyper parameter tuning will be added later.
For now, the following parameters were used: 
- TD Learning Rate : 0.1
- Discount factor : 0.99

For now, these values were randomly chosen. Using Q learning, the Car was able to ascend to the hilltop in a much easier fashion compared to how it did initially, in 10,000 steps.

### Reinforcement Learning to Train On A Frozen Lake
We have considered two conditions, when the lake is either slippery or not. It has been seen that the reward is higher on an average for the non slippery one than the slippery one due to the fact that the whole lake is strongly deterministic in nature, as well as the randomness of the stochastic slipping of the Agent. 
- TD Learning Rate : 0.8
- Discount factor : 0.95

### Reinforcement Learning to Train Play BlackJack
The agent plays to learn Blackjack rather quickly and win games. :) 
- TD Learning Rate : 0.1
- Discount factor : 0.95
