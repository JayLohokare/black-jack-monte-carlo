# black-jack-monte-carlo
Black Jack game Monte Carlo implementation based on Open Gym

Udemy Deep reinforcement learning nano-degree Monte Carlo assignment

Points about Monte-Carlo:
1. Alpha - Decides how rewards propogate through actions. Alpha determines if the agent cares about reward many actions down the line, or immediate reward. Alphas propogate in same episode

2. Epsilon - Epsilon is concerned with how explorative/exploitative an agent is. If we know some action gives high reward, going for it is called exploitative nature. Checking out not so profitable actions to 'explore' is explorative nature. Epsilon if 1, agent will strictly treat all actions with equal probability. 

This code contains constant Alpha decaying Epsilon implementation of Black Jack game  
