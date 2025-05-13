A diffusion model is utilized for trajectory generation within a 10 × 10 grid, where obstacles must be avoided. 
- This model is structured around a UNet architecture and receives the obstacle map as input. 
- Training is conducted in a data-driven manner, with reinforcement learning presenting a potential implementation strategy.
    - The training tuple consists of pairs of an input obstacle map and a generated trajectory.
    - The test tuple follows the same structure as the training tuple, except that these data are unseen during training and are used solely to evaluate the model’s performance.
