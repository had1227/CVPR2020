### RL-CycleGAN: Reinforcement Learning Aware Simulation-to-Real
- **Oral presentation** [(Video)](http://cvpr20.s3-website-us-west-2.amazonaws.com/CVPR20/CVPR20/9770/9770-oral.mp4)

- Contributions
    - RL-CycleGAN adapts simulated images to be more realistic while aslo useful for RL using a RL-scene consistency loss
    - Significantly improves data efficiency for real world robotic grasping
    
- Overview
    - ![semantic_map_overview](./img/RL-CycleGAN_overview.png)
    
- Method
    - ![semantic_map_network](./img/RL-CycleGAN_method.png)
    - Use RL-scene consistency loss
            
### SuperGlue: Learning Feature Matching With Graph Neural Networks
- **Oral presentation** [(Video)](http://cvpr20.s3-website-us-west-2.amazonaws.com/CVPR20/CVPR20/7621/7621-oral.mp4)

- Contributions
    - It proposed a method for vision-language navigation which solves auxiliary tasks to take advantage of the additional training signals derived from the semantic information.
    
- Overview
    - ![aux_RN_overview](./img/SuperGlue_overview.png)

- Method
    - ![aux_RN_network](./img/SuperGlue_method.png)
    - Auxiliary tasks
        - Trajectory retelling 
        - Progress estimation
        - Cross-modal matching
        - Angle predictions
    - Graph map
        - Jointly use imitation learning and reinforcement learning for the navigation
    

