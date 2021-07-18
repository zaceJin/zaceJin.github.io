# Stable Baselines Study notes
## Choose Your Algorithms
  1. For Discrete actions:   
      a. Single Process: DQN and its extensions are suitable, ACER.     
      b. Multiprocessed: PPO2, A2C and its extension   
  2. For Countinuous Actions:   
      a. Single Process: SOTA  
      b. PPO2, TRPO, A2C   
      c. Always take hyperparameters from look [RL zoo](https://github.com/araffin/rl-baselines-zoo)  

## Policy Networks 
  1. CnnPolicies are for images only. MlpPolicies are made for other type of features (e.g. robot joints)
  2. 
