# 强化学习学习笔记  RL Study Notes 08\07\2021
## Initialize My GYM Env
   1. Continuous action and obs space for Robotics locomotion. 
   2. Discrete action and obs space for Game (Atari). 
   3. Always normalize action and Obs space:   
     `action_space = spaces.Box(low=-1., 
                                       high=1., 
                                       shape=(cf.A_DIM,),
                                       dtype=np.float32)`  
       A_DIM is number of Joints for the robot.
    
 ## Tricks and Tips
  1. For tuned Hyperparameters: look [RL zoo](https://github.com/araffin/rl-baselines-zoo)
  2. always normalize your observation space when you can (if you know the boundaries)    
  RL is rely on Gaussain distribution for continuous. look [Stable Baseline](https://stable-baselines.readthedocs.io/en/master/guide/rl_tips.html)
  3. 
