# Awesome Isaac Sim (Updating!)

## 📝 Introduction

This is a list of resources related to NVIDIA Isaac Sim, inspired by [awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym).  
The development progression is: Isaac Gym → Isaac Sim → Orbit → Isaac Lab, where the latter two are built on Isaac Sim.  
Because Isaac Gym is lightweight and efficient, it is still widely used in RL research, but Isaac Sim’s ecosystem and adoption are growing rapidly.  
If this list helps your research, please give it a star and fork!  
**If your Isaac Sim–based work is accepted at top conferences or journals, feel free to open an issue or pull request to update this list.**

## Contribute to this list

We encourage you to add your Isaac Sim–related work to this list! You can  
- **Submit a Pull Request** to include new algorithms, environment configs, benchmarks, etc.

## 🔥 Papers & Research using Isaac Sim / Isaac Lab / Omniverse Isaac

- [“Towards Building AI-CPS with NVIDIA Isaac Sim: An Industrial Benchmark and Case Study for Robotics Manipulation” (2023)](https://arxiv.org/abs/2308.00055) — proposes a public robotics manipulation benchmark built on Omniverse Isaac Sim, with multiple tasks and AI controller evaluation. :contentReference[oaicite:0]{index=0}  
- [“GRADE: Generating Realistic and Dynamic Environments for Robotics Research with Isaac Sim” (2023)](https://arxiv.org/abs/2303.04466) — presents GRADE, a framework built on Isaac Sim to generate dynamic environments, synthetic datasets, and repeatable experiments. :contentReference[oaicite:1]{index=1}  
- [“Orbit: A Unified Simulation Framework for Interactive Robot Learning Environments” (2023)](https://arxiv.org/abs/2301.04195) — a simulation framework built on Isaac Sim with benchmark tasks, sensor modalities, and learning wrappers. :contentReference[oaicite:2]{index=2}  
- [“Sim-to-Real gap in RL: Use Case with TIAGo and Isaac Sim / Isaac Gym” (2024)](https://arxiv.org/abs/2403.07091) — explores sim-to-real transfer using TIAGo manipulator in both Isaac Sim and Isaac Gym. :contentReference[oaicite:3]{index=3}  
- [“Mind and Motion Aligned: A Joint Evaluation IsaacSim Benchmark for Task Planning and Low-Level Policies in Mobile Manipulation” (2025)](https://arxiv.org/abs/2508.15663) — proposes Kitchen-R benchmark built with Isaac Sim, combining high-level planning and low-level control in mobile manipulation. :contentReference[oaicite:4]{index=4}  
- [“Automation in Unstructured Production Environments Using Isaac Sim”](https://www.sciencedirect.com/science/article/pii/S2212827124013301) — applies Isaac Sim for industrial robot automation in complex real-world manufacturing scenarios. :contentReference[oaicite:5]{index=5}  
- “Robotics Simulation – A Comparison of Two State-of-the-Art Solutions” (2022) — compares Gazebo vs Isaac Sim for mobile robots / sensors / ROS integration. :contentReference[oaicite:6]{index=6}  

---

## 🚩 Official Resource

[Isaac Lab](https://github.com/isaac-sim/IsaacLab)  
[Tutorial for Isaac Sim](https://docs.omniverse.nvidia.com/isaacsim/latest/core_api_tutorials/tutorial_core_hello_world.html)  
[omniIsaacSimEnvs](https://github.com/isaac-sim/OmniIsaacGymEnvs)  
[Isaac ROS projects](https://github.com/NVIDIA-ISAAC-ROS)  
[RL algorithms: skrl](https://github.com/Toni-SM/skrl)  
[rl_games](https://github.com/Denys88/rl_games)  
[Unitree Go2, Unitree G1 support for Nvidia Isaac Lab](https://github.com/abizovnuralem/go2_omniverse)  
[connect Gazebo to Omniverse](https://github.com/gazebosim/gz-omni)  
[MetaGraspNet](https://github.com/maximiliangilles/MetaGraspNet)  
[Orbit-surgical](https://github.com/orbit-surgical/orbit-surgical)

---

## 🔧 Community Projects & Extensions (selected, star ≥ 20)

- [IsaacSim](https://github.com/isaac-sim/IsaacSim) — NVIDIA Isaac Sim core repo.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/IsaacSim?style=social) 
- [IsaacLab](https://github.com/isaac-sim/IsaacLab) — unified robot learning framework built on Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/IsaacLab?style=social)
- [IsaacGymEnvs](https://github.com/isaac-sim/IsaacGymEnvs) — RL environment collection for Isaac Gym / Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/IsaacGymEnvs?style=social) 
- [OmniIsaacGymEnvs](https://github.github.io/isaac-sim/OmniIsaacGymEnvs) — RL examples built on Isaac Sim (omni.isaac core/gym).  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/OmniIsaacGymEnvs?style=social) 
- [IsaacSim-ros_workspaces](https://github.com/isaac-sim/IsaacSim-ros_workspaces) — ROS/ROS2 workspaces integrated with Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/IsaacSim-ros_workspaces?style=social) 
- [isaac-launchable](https://github.com/isaac-sim/isaac-launchable) — pre-configured Isaac Sim / Isaac Lab environment via Brev Launchable.  
  ![GitHub stars](https://img.shields.io.github/stars/isaac-sim/isaac-launchable?style=social) 
- [isaacsim-app-template](https://github.com/isaac-sim/isaacsim-app-template) — template for building Isaac Sim Kit apps / extensions.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/isaacsim-app-template?style=social)
- [IsaacAutomator](https://github.com/isaac-sim/IsaacAutomator) — tools to deploy Isaac Sim / Isaac Lab to cloud environments.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/IsaacAutomator?style=social) 
- [MetaToolEU/MT_Isaac_sim](https://github.com/MetaToolEU/MT_Isaac_sim) — simulating dual UR arms in Isaac Sim with MPC, collision avoidance, path planning.  
  ![GitHub stars](https://img.shields.io/github/stars/MetaToolEU/MT_Isaac_sim?style=social) 
- [MuammerBay/isaac_so_arm101](https://github.com/MuammerBay/isaac_so_arm101) — task environment projects for SO-ARM100 / SO-ARM101 using Isaac Lab / Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/MuammerBay/isaac_so_arm101?style=social) 
- [agilexrobotics/Limo-Isaac-Sim](https://github.com/agilexrobotics/Limo-Isaac-Sim) — integration of LIMO mobile robot URDF into Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/agilexrobotics/Limo-Isaac-Sim?style=social) 
- [unitreerobotics/unitree_sim_isaaclab](https://github.com/unitreerobotics/unitree_sim_isaaclab) — Unitree robot simulation in Isaac Lab / Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/unitreerobotics/unitree_sim_isaaclab?style=social) 
- [unitreerobotics/unitree_rl_lab](https://github.com/unitreerobotics/unitree_rl_lab) — RL algorithms/environment for Unitree robots using Isaac Lab / Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/unitreerobotics/unitree_rl_lab?style=social) 
- [abizovnuralem/go2_omniverse](https://github.com/abizovnuralem/go2_omniverse) — support for Unitree Go2 / G1 in Nvidia Isaac Lab / Sim (digital-twin, ROS2).  
  ![GitHub stars](https://img.shields.io/github/stars/abizovnuralem/go2_omniverse?style=social) 
- [j3soon/OmniIsaacGymEnvs-UR10Reacher](https://github.com/j3soon/OmniIsaacGymEnvs-UR10Reacher) — UR10 reacher RL example built on Isaac Sim / omni.gym.  
  ![GitHub stars](https://img.shields.io/github/stars/j3soon/OmniIsaacGymEnvs-UR10Reacher?style=social)

---

## ⭐ Related awesome lists

- [awesome-wheel-slam](https://github.com/sjtuyinjie/awesome-wheel-slam)  
- [awesome-LiDAR-Visual-SLAM](https://github.com/sjtuyinjie/awesome-LiDAR-Visual-SLAM)  
- [awesome-LiDAR-Camera-Calibration](https://github.com/Deephome/Awesome-LiDAR-Camera-Calibration)  
- [awesome-SLAM](https://github.com/SilenceOverflow/Awesome-SLAM)  
- [awesome-SLAM-datasets](https://github.com/youngguncho/awesome-slam-datasets)  
- [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)  
- [awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning)  
- [awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym)  

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sjtuyinjie/awesome-isaac-sim&type=Timeline)](https://star-history.com/#sjtuyinjie/awesome-isaac-sim&Timeline)
