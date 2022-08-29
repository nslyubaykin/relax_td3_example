# Example TD3 implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_td3_example/blob/master/td3_tutorial.ipynb) of twin delayed deep deterministic policy gradient (TD3) with ReLAx.

TD3 actor was trained on Walker2d-v2 Mujoco Gym environment for 1m env-steps. 

The graph of average return vs environment step is shown below (logs done every 10k steps):

![td3_training](https://github.com/nslyubaykin/relax_td3_example/blob/master/td3_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![td3_q_func](https://github.com/nslyubaykin/relax_td3_example/blob/master/td3_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187178917-74855a55-6d0e-4ec3-9978-ea5ccbc4c644.mp4
