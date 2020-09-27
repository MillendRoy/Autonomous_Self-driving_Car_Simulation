# Autonomous_Self-driving_Car_Simulation
1. Graphics creation using Kivy modules in Python. A car with 3 sensors in front used in the simulation.
2. Deep Q-Learning reinforcement techniques used  with specific reward policies where the taxi runs downtown to the airport and back.
3. Sand used for its simulation so that the taxi can learn through experiences stored in a batch of 100.
4. Reward = -1 given to the taxi when it crashes into the sand or reaches outskirts of the city, Reward = -0.2 given when it moves further away from the destination, Reward = +0.1 given when it approaches in correct direction of the destination, Reward =+1 given when it reaches the goal.
