# Pragya Rathal


I am a third-year undergraduate in Civil Engineering at **IIT (BHU), Varanasi**, working toward research in **autonomous robotics and socially intelligent robots**. My interests lie in the systems that allow robots to perceive their surroundings, understand dynamic environments, make decisions, and act reliably around people.

My current work is concentrated in **LiDAR-based 3D perception, learning-based navigation, and human movement modelling**. I am particularly interested in extending these foundations toward **human-aware navigation, human–robot interaction, and social robot behaviour**.

---

## Research interests

- **Robot perception:** 3D LiDAR, point-cloud processing, ground segmentation, terrain understanding, visual representations.
- **Autonomous navigation:** traversability estimation, local planning, trajectory tracking, perception-to-action pipelines.
- **Learning for robotics:** reinforcement learning, representation learning, vision-based policies, sim-to-real questions.
- **Social and human-centred robotics:** human-aware motion, locomotion and intent prediction, interactive robot systems.

## Selected robotics work

### 3D LiDAR perception and terrain understanding
Developing ROS 2 perception components around **Patchwork++** and Livox point clouds, with a focus on ground segmentation and terrain interpretation for mobile-robot navigation.

- Working with point-cloud processing, sensor-specific preprocessing, and ROS 2 integration.
- Building a terrain-analysis pipeline that separates ground perception from downstream traversability estimation.
- Exploring the use of ground geometry and obstacle structure to support navigation in constrained environments.

[Patchwork++ / Livox work](https://github.com/Pragya-rathal/patchworkpluslivox) · [ROS implementation](https://github.com/Pragya-rathal/patchwork-plusplus-ros)

### Learning-based visual navigation
Investigating whether pretrained **Vision Transformer (ViT)** representations can provide useful state features for reinforcement learning in a visual navigation task.

- Comparing image-based policy learning with policies using frozen ViT embeddings.
- Implementing the experimental pipeline in PyTorch and Gymnasium.
- Studying the relationship between visual representation quality and policy learning.

[Project repository](https://github.com/Pragya-rathal/Perception-Aware-Reinforcement-Learning-using-Vision-Transformer-Features)

### EMG-based locomotion modelling
Building a signal-processing and learning pipeline for EMG windows, muscle-synergy analysis, and locomotion forecasting. This work connects human movement signals with predictive models—a direction I hope to develop further for human-aware and assistive robotics.

- EMG preprocessing and window-level dataset construction.
- Non-negative Matrix Factorization (NMF) for muscle-synergy extraction.
- Temporal modelling and evaluation for anticipatory gait/locomotion prediction.

[Preprocessing pipeline](https://github.com/Pragya-rathal/gait_preprocessing_pipeline) · [Forecasting work](https://github.com/Pragya-rathal/gait-hopefully-final)

### UAV simulation and learning-based control
Exploring simulation environments and learning methods for aerial robotics, including multi-agent reinforcement learning and UAV system optimisation.

[UAV simulation work](https://github.com/Pragya-rathal/gym-pybullet-drones) · [UAV federated-learning simulation](https://github.com/Pragya-rathal/uav-fl-clustering-simulation)

---

## Technical toolkit

| Area | Tools and methods |
|---|---|
| Robotics middleware | ROS 2, ROS, RViz, TF, rosbag, colcon |
| Perception | 3D LiDAR, point clouds, Patchwork++, Open3D, OpenCV |
| Learning | PyTorch, reinforcement learning, CNNs, Vision Transformers, sequence models |
| Robotics & simulation | Gazebo, PyBullet, Gymnasium |
| Programming | Python, C++, C |
| Development | Linux, Git, CMake, Docker |

## Current direction

I am looking to deepen my research in **autonomous mobile robots and social robotics**, especially at the intersection of:

1. Robust 3D perception and navigation in real-world environments.
2. Human-aware navigation and prediction of human motion or intent.
3. Learning-based robot decision-making from visual and multimodal observations.
4. Perception and control architectures for robots operating safely and naturally around people.

I value work that connects algorithmic ideas to functioning robotic systems, with careful evaluation in simulation and, where possible, on hardware.

---

## Contact

IIT (BHU), Varanasi · India

- [LinkedIn](https://www.linkedin.com/in/pragya-rathal-6b97a5321/)
- [Resume](https://drive.google.com/file/d/1iod6_lznt7o4gU8SUy7Yoapkj2mTRfSm/view?usp=sharing)


*Interested in research discussions and opportunities in autonomous robotics, robot perception, navigation, and human-centred/social robotics.*
