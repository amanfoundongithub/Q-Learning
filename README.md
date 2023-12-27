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
