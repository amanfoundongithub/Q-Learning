### Reinforcement Learning to Train An Automated Taxi

The algorithm used to train the driver is Q-Learning. The Taxi is taken from OpenAI's Taxi-v3, an open source implementation of the Taxi problem. Hyper parameter tuning will be added later.
For now, the following parameters were used: 
- TD Learning Rate : 0.25
- Discount factor : 0.8

For now, these values were randomly chosen. Using Q learning, the driver was able to learn to drive with minimal loss. Starting from State 123 [Taxi has 500 states], we reached destination in 19 steps, an optimal value.
