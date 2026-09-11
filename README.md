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

- [“Play2Perfect: What Matters in Dexterous Play Pretraining for Precise Assembly?” (2026, CoRL)](https://arxiv.org/abs/2606.26428) — two-stage Isaac Sim/Isaac Lab RL pipeline: free-space play pretraining followed by contact-rich assembly finetuning, with zero-shot sim-to-real on tight insertion and screwing.  
- [“SimToolReal: An Object-Centric Policy for Zero-Shot Dexterous Tool Manipulation” (2026)](https://arxiv.org/abs/2602.16863) — procedural tool-like object generation in Isaac Sim/Isaac Lab and a single RL policy for zero-shot dexterous tool manipulation (DexToolBench).  
- [“FlatLab: A Unified Methodology Framework and Simulation-Based Benchmark for Robotic Manipulation of Flat Objects” (2026, ICML)](https://arxiv.org/abs/2608.14049) — introduces FlatLab, a simulation benchmark built on Isaac Sim 4.5.0 with 100+ rigid/deformable flat objects, multi-modal data collection, and standardized evaluation protocols.  
- [“SIMPLE: Simulation-Based Policy Learning and Evaluation for Humanoid Loco-manipulation” (2026, CoRL)](https://arxiv.org/abs/2606.08278) — presents a humanoid loco-manipulation testbed coupling MuJoCo dynamics with Isaac Sim photorealistic rendering; 60 whole-body tasks, 50 indoor scenes, and 1,000+ object assets.  
- [“NVIDIA Isaac Sim: Enabling Scalable, GPU-Accelerated Simulation for Robotics” (2026)](https://arxiv.org/abs/2606.03551) — systematic survey of Isaac Sim architecture, usage patterns across five application domains, and comparison with other simulators.  
- [“Isaac Lab: A GPU-Accelerated Simulation Framework for Multi-Modal Robot Learning” (2025)](https://arxiv.org/abs/2511.04831) — official Isaac Lab framework paper covering GPU-native physics, RTX rendering, Gymnasium API, and integrations with RSL-RL, RL-Games, SKRL, etc.  
- [“BeyondMimic: From Motion Tracking to Versatile Humanoid Control via Guided Diffusion” (2025)](https://arxiv.org/abs/2508.08241) — Isaac Lab-based humanoid motion tracking framework (LAFAN1-scale sim-to-real-ready motions) with steerable test-time control.  
- [“LabUtopia: High-Fidelity Simulation and Hierarchical Benchmark for Scientific Embodied Agents” (2025, NeurIPS)](https://arxiv.org/abs/2505.22634) — scientific lab simulation suite built on Isaac Sim with chemical engine, 30 tasks, and hierarchical LabBench benchmark.  
- [“RoboVerse: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning” (2025)](https://arxiv.org/abs/2504.18904) — unified simulation platform (MetaSim) supporting Isaac Sim/Isaac Lab alongside MuJoCo, SAPIEN, Genesis, etc.  
- [“Mind and Motion Aligned: A Joint Evaluation IsaacSim Benchmark for Task Planning and Low-Level Policies in Mobile Manipulation” (2025)](https://arxiv.org/abs/2508.15663) — proposes Kitchen-R benchmark built with Isaac Sim, combining high-level planning and low-level control in mobile manipulation.  
- [“ASAP: Aligning Simulation and Real-World Physics for Learning Agile Humanoid Whole-Body Skills” (2025, RSS)](https://arxiv.org/abs/2502.01143) — humanoid whole-body skill learning with sim-to-real alignment; supports Isaac Gym, Isaac Sim/Isaac Lab, and Genesis backends.  
- [“Wheeled Lab: Modern Sim2Real for Low-cost, Open-source Wheeled Robotics” (2025, CoRL)](https://arxiv.org/abs/2502.07380) — integrates low-cost wheeled platforms (HOUND, MuSHR) with Isaac Lab; demonstrates zero-shot sim-to-real for drifting, elevation traversal, and visual navigation.  
- [“Sim-to-Real Transfer for Mobile Robots with Reinforcement Learning: from NVIDIA Isaac Sim to Gazebo and Real ROS 2 Robots” (2025)](https://arxiv.org/abs/2501.02902) — end-to-end PPO navigation pipeline trained in Isaac Sim, benchmarked against Nav2, and deployed on real TurtleBot 4 Lite via ROS 2.  
- [“Sim-to-Real gap in RL: Use Case with TIAGo and Isaac Sim / Isaac Gym” (2024)](https://arxiv.org/abs/2403.07091) — explores sim-to-real transfer using TIAGo manipulator in both Isaac Sim and Isaac Gym.  
- [“Towards Building AI-CPS with NVIDIA Isaac Sim: An Industrial Benchmark and Case Study for Robotics Manipulation” (2023)](https://arxiv.org/abs/2308.00055) — proposes a public robotics manipulation benchmark built on Omniverse Isaac Sim, with multiple tasks and AI controller evaluation.  
- [“GRADE: Generating Realistic and Dynamic Environments for Robotics Research with Isaac Sim” (2023)](https://arxiv.org/abs/2303.04466) — presents GRADE, a framework built on Isaac Sim to generate dynamic environments, synthetic datasets, and repeatable experiments.  
- [“Orbit: A Unified Simulation Framework for Interactive Robot Learning Environments” (2023)](https://arxiv.org/abs/2301.04195) — a simulation framework built on Isaac Sim with benchmark tasks, sensor modalities, and learning wrappers (predecessor of Isaac Lab).  
- [“Automation in Unstructured Production Environments Using Isaac Sim”](https://www.sciencedirect.com/science/article/pii/S2212827124013301) — applies Isaac Sim for industrial robot automation in complex real-world manufacturing scenarios.  
- “Robotics Simulation – A Comparison of Two State-of-the-Art Solutions” (2022) — compares Gazebo vs Isaac Sim for mobile robots / sensors / ROS integration.  

---

## 🚩 Official Resource

[Isaac Lab](https://github.com/isaac-sim/IsaacLab)  
[Isaac Lab-Arena](https://github.com/isaac-sim/IsaacLab-Arena) — composable task curation and policy evaluation at scale (G1/GR1 humanoid, imitation learning).  
[Isaac-GR00T](https://github.com/NVIDIA/Isaac-GR00T) — NVIDIA foundation model for generalist robots (N1.x series).  
[GR00T Whole-Body Control](https://github.com/NVlabs/GR00T-WholeBodyControl) — unified platform for humanoid whole-body control development and deployment.  
[Tutorial for Isaac Sim](https://docs.omniverse.nvidia.com/isaacsim/latest/core_api_tutorials/tutorial_core_hello_world.html)  
[omniIsaacSimEnvs](https://github.com/isaac-sim/OmniIsaacGymEnvs)  
[Isaac ROS projects](https://github.com/NVIDIA-ISAAC-ROS)  
[RL algorithms: skrl](https://github.com/Toni-SM/skrl)  
[rl_games](https://github.com/Denys88/rl_games)  
[RSL-RL](https://github.com/leggedrobotics/rsl_rl)  
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
- [OmniIsaacGymEnvs](https://github.com/isaac-sim/OmniIsaacGymEnvs) — RL examples built on Isaac Sim (omni.isaac core/gym).  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/OmniIsaacGymEnvs?style=social) 
- [IsaacLab-Arena](https://github.com/isaac-sim/IsaacLab-Arena) — composable simulation framework for diverse robot tasks and policy evaluation at scale.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/IsaacLab-Arena?style=social) 
- [fan-ziqi/robot_lab](https://github.com/fan-ziqi/robot_lab) — RL extension library for diverse robots (Unitree G1/H1, Booster T1, Deeprobotics, etc.) built on Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/fan-ziqi/robot_lab?style=social) 
- [HybridRobotics/whole_body_tracking](https://github.com/HybridRobotics/whole_body_tracking) — BeyondMimic humanoid motion tracking training on Isaac Lab (LAFAN1-scale sim-to-real motions).  
  ![GitHub stars](https://img.shields.io/github/stars/HybridRobotics/whole_body_tracking?style=social) 
- [NVlabs/ProtoMotions](https://github.com/NVlabs/ProtoMotions) — GPU-accelerated humanoid simulation and learning (AMASS-scale motion learning, Isaac Sim/Isaac Lab/Newton backends).  
  ![GitHub stars](https://img.shields.io/github/stars/NVlabs/ProtoMotions?style=social) 
- [RoboVerseOrg/RoboVerse](https://github.com/RoboVerseOrg/RoboVerse) — unified robot learning platform with MetaSim abstraction over Isaac Sim, MuJoCo, SAPIEN, Genesis, etc.  
  ![GitHub stars](https://img.shields.io/github/stars/RoboVerseOrg/RoboVerse?style=social) 
- [tylerlum/simtoolreal](https://github.com/tylerlum/simtoolreal) — zero-shot dexterous tool manipulation via procedural objects in Isaac Sim/Isaac Lab (DexToolBench).  
  ![GitHub stars](https://img.shields.io/github/stars/tylerlum/simtoolreal?style=social) 
- [kushal2000/play2perfect](https://github.com/kushal2000/play2perfect) — two-stage RL for contact-rich assembly: play pretraining + assembly finetuning in Isaac Sim/Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/kushal2000/play2perfect?style=social) 
- [LeCAR-Lab/ASAP](https://github.com/LeCAR-Lab/ASAP) — agile humanoid whole-body skills with sim-to-real physics alignment (Isaac Gym / Isaac Sim / Isaac Lab).  
  ![GitHub stars](https://img.shields.io/github/stars/LeCAR-Lab/ASAP?style=social) 
- [Zhefan-Xu/NavRL](https://github.com/Zhefan-Xu/NavRL) — safe UAV navigation RL trained in NVIDIA Isaac Sim with ROS1/ROS2 deployment.  
  ![GitHub stars](https://img.shields.io/github/stars/Zhefan-Xu/NavRL?style=social) 
- [Rui-li023/LabUtopia](https://github.com/Rui-li023/LabUtopia) — NeurIPS 2025 scientific embodied agent benchmark with chemical simulation on Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/Rui-li023/LabUtopia?style=social) 
- [TIERS/isaac-marl-mobile-manipulation](https://github.com/TIERS/isaac-marl-mobile-manipulation) — multi-agent RL for mobile manipulation in NVIDIA Isaac Sim.  
  ![GitHub stars](https://img.shields.io/github/stars/TIERS/isaac-marl-mobile-manipulation?style=social) 
- [j3soon/OmniIsaacGymEnvs-DofbotReacher](https://github.com/j3soon/OmniIsaacGymEnvs-DofbotReacher) — Dofbot reacher RL sim-to-real example on Isaac Sim / omni.gym.  
  ![GitHub stars](https://img.shields.io/github/stars/j3soon/OmniIsaacGymEnvs-DofbotReacher?style=social) 
- [engineai-robotics/engineai_rl_lab](https://github.com/engineai-robotics/engineai_rl_lab) — RL environments for EngineAI robots based on Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/engineai-robotics/engineai_rl_lab?style=social) 
- [physical-superintelligence-lab/SIMPLE](https://github.com/physical-superintelligence-lab/SIMPLE) — humanoid loco-manipulation benchmark (MuJoCo + Isaac Sim rendering).  
  ![GitHub stars](https://img.shields.io/github/stars/physical-superintelligence-lab/SIMPLE?style=social) 
- [UWRobotLearning/WheeledLab](https://github.com/UWRobotLearning/WheeledLab) — mobile robotics environments and sim-to-real workflow integrated with Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/UWRobotLearning/WheeledLab?style=social) 
- [louislelay/kinova_isaaclab_sim2real](https://github.com/louislelay/kinova_isaaclab_sim2real) — Kinova Gen3 training in Isaac Lab with sim-to-real transfer and ROS deployment.  
  ![GitHub stars](https://img.shields.io/github/stars/louislelay/kinova_isaaclab_sim2real?style=social) 
- [DH-Ng/TacEx](https://github.com/DH-Ng/TacEx) — tactile sensing extension for Isaac Sim / Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/DH-Ng/TacEx?style=social) 
- [zhaozijie2022/LocoWheeledLegged](https://github.com/zhaozijie2022/LocoWheeledLegged) — RL-based legged-wheeled robot locomotion sim-to-real on Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/zhaozijie2022/LocoWheeledLegged?style=social) 
- [abmoRobotics/RLRoverLab](https://github.com/abmoRobotics/RLRoverLab) — rover and space-related RL environments for Isaac Sim / Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/abmoRobotics/RLRoverLab?style=social) 
- [sahars93/RL-Navigation](https://github.com/sahars93/RL-Navigation) — 2D LiDAR mobile robot navigation RL with Isaac Sim → Gazebo → real ROS 2 deployment.  
  ![GitHub stars](https://img.shields.io/github/stars/sahars93/RL-Navigation?style=social) 
- [isaac-sim/Sim-to-Real-SO-101-Workshop](https://github.com/isaac-sim/Sim-to-Real-SO-101-Workshop) — end-to-end Physical AI workshop: SO-101 arm sim-to-real with Isaac Lab.  
  ![GitHub stars](https://img.shields.io/github/stars/isaac-sim/Sim-to-Real-SO-101-Workshop?style=social) 
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


<a href="https://www.star-history.com/?repos=sjtuyinjie%2Fawesome-isaac-sim&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=sjtuyinjie/awesome-isaac-sim&type=date&theme=dark&legend=top-left&sealed_token=Uwc8jQBjLpS0ki1uPjIpYixhl9t5B9UbinNfjCCpQGVUEAaW1kwzVuVMAIRhARuxZu-hixedWFbVOK7Elope7SGgNejk5wQoAMlhNU2dJpy5fFvZ2MZXT0UKTBPEnLVMQPdYXWIRbjdhJji4Jj09fYxiKkSPtab_-FjVfRQFvYhuyuVTuoO9dbZN85ip" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=sjtuyinjie/awesome-isaac-sim&type=date&legend=top-left&sealed_token=Uwc8jQBjLpS0ki1uPjIpYixhl9t5B9UbinNfjCCpQGVUEAaW1kwzVuVMAIRhARuxZu-hixedWFbVOK7Elope7SGgNejk5wQoAMlhNU2dJpy5fFvZ2MZXT0UKTBPEnLVMQPdYXWIRbjdhJji4Jj09fYxiKkSPtab_-FjVfRQFvYhuyuVTuoO9dbZN85ip" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=sjtuyinjie/awesome-isaac-sim&type=date&legend=top-left&sealed_token=Uwc8jQBjLpS0ki1uPjIpYixhl9t5B9UbinNfjCCpQGVUEAaW1kwzVuVMAIRhARuxZu-hixedWFbVOK7Elope7SGgNejk5wQoAMlhNU2dJpy5fFvZ2MZXT0UKTBPEnLVMQPdYXWIRbjdhJji4Jj09fYxiKkSPtab_-FjVfRQFvYhuyuVTuoO9dbZN85ip" />
 </picture>
</a>
