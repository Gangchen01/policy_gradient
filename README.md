# Reinforcement Learning using Policy Gradient
Algorithm: REINFORCE Actor- Critic  

OpenAI environment: CartPole

Requirements:
-------------

Tensorflow 1.0.1

Openai Gym 0.81


Run Command:
------------
    python policyGradient.py
    
Output:
-------
Reward Monitor will appear, the Model learns with each episode (you can see in the monitor as total reward increases) 
**Note:** It Converges to 200 because cartpole in openai gym 0.81 terminates at 200 steps in each rollout.

![alt text](https://github.com/srikanthmalla/policy_gradient/blob/master/reward%20vs%20episodes.png "Reward_vs_Episodes")

