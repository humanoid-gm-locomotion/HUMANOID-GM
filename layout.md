<!-- * work on contents L949 onward (Hardware demonstration) in index.html

Here is the outline 

## Per-Terrain Velocity Tracking 
We deploy the trained RL policy on a Unitree G1 humanoid robot to validate our approach in real world.

### Terrain 1: Basalt 
* Tile assets/ours/videos/hardware/basalt/*.mp4
* We might make Nx3 (N is number of velocities and 3 are policy type numbers)

### Terrain 2: Beach Volleyball 
* Use assets/ours/videos/hardware/campus

### Terrain 3: Beach 
* Use assets/ours/videos/hardware/beach
* We might move this to last section for showcase 

## Terrain-Transition 
* Use assets/ours/videos/hardware/terrain_transition/Ours.mp4 and PPO_3D_RFT.mp4 

## Contact Model Ablation 
* Mention box intrusion experiment: videos in assets/ours/videos/simulation/contact_model
* Paste plot from assets/ours/videos/simulation/contact_model/contact_model_ablation.png

## Policy Performance per Contact Model

### Task1: Circular Walking on Flat Terrain
* mention assets/ours/videos/simulation/policy_comparison/rough_terrain/*.mp for now (I will replace video later)

### Task2: Circular Walking on Rough Terrain 
* mention assets/ours/videos/simulation/policy_comparison/rough_terrain/*.mp4

### Task3: Forward Walking on Deep Sand 
* mention assets/ours/videos/simulation/policy_comparison/deep_sand/*.mp4 -->


<!-- * For Terrain 3: Beach, I want to tile video 2x2 and first column for PPO_3D_RFT and second for PPO_Rigid. (last entry will be empty)
* N/A is good idea? Is it better to replace with assets/ours/icons/fail.png and Fail text? 
* Can you replace appendix with tables in /home/jkamohara3/isaac/ral26/RAL/RAL_Learning_Humanoid_Locomotion_on_Granular_Terrain/First_draft/Appendix.tex ? You might need to figure out macro symbols by refering to /home/jkamohara3/isaac/ral26/RAL/RAL_Learning_Humanoid_Locomotion_on_Granular_Terrain/shortcut.tex -->

<!-- * Can you also add observation tables ? You can refer to paragraphs in /home/jkamohara3/isaac/ral26/RAL/RAL_Learning_Humanoid_Locomotion_on_Granular_Terrain/First_draft/Method.tex. 
* Can you add assets/ours/images/basalt_vel_tracking.png and assets/ours/images/beach_volleyball_vel_tracking.png after each video tile?  -->

* observation table needs a quite a bit of improvement. Basically, it should have teacher actor, teacher encoder, student actor, student encoder, and critic. Look at /Users/jnskkmhr/lab_ws/ral_26/RAL_Learning_Humanoid_Locomotion_on_Granular_Terrain/First_draft/method.tex for reference. If 5 items are two long, you can make table horizontally scrolable. 