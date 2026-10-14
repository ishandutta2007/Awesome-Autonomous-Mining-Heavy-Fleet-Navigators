# Awesome-Autonomous-Mining-Heavy-Fleet-Navigators

## Top Autonomous Mining Heavy Fleet Navigators Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Autonomous Haulage, Fleet Dispatch & Unmanned Excavation*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Mining Heavy Fleet Navigators**. These tools enable mining operators to coordinate autonomous haul trucks, excavators, and loaders in harsh environments—optimizing dispatch, reducing fuel consumption, and improving safety through deterministic fleet algorithms.



**Examples** include Caterpillar MineStar, Komatsu FrontRunner, Hexagon Mining, Sandvik AutoMine, Epiroc Mobius, ASI Mining, SafeAI, Teleo, Pronto, and RPMGlobal (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, open mine simulation, and transparent dispatch algorithm development—ideal for mining engineers, researchers, and developers seeking vendor-independent fleet automation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Caterpillar MineStar](https://www.cat.com/en_US/by-industry/mining/surface-mining/surface-technology.html)**  

  Comprehensive mining technology suite with Command for autonomous haulage, Fleet for dispatch optimization, and Health for equipment monitoring. Manages the world's largest autonomous truck fleet across multiple mine sites.



- **[Komatsu FrontRunner](https://www.komatsu.com/en/solutions/mining/autonomous-haulage/)**  

  Autonomous haulage system with proven deployments at large open-pit mines globally. Features GPS-based navigation, obstacle detection, and integration with dispatch systems.



- **[Hexagon Mining](https://hexagon.com/industries/mining)**  

  Mining technology platform with autonomous drilling, fleet management, and mine planning. Features real-time visualization and integration across the mining value chain.



- **[Sandvik AutoMine](https://www.rocktechnology.sandvik/en/products/automation/automine/)**  

  Autonomous mining system for underground loaders and trucks. Enables remote operation from surface control rooms with teleoperation fallback.



- **[Epiroc Mobius](https://www.epiroc.com/en-us/products/automation/mobius)**  

  Fleet management and automation platform for underground mining. Features traffic management, task scheduling, and real-time equipment tracking.



- **[ASI Mining](https://www.asimining.com/)**  

  Autonomous vehicle technology for mining, providing retrofit kits for existing haul trucks. Features obstacle detection and path planning.



- **[SafeAI](https://safeai.com/)**  

  Autonomous retrofit platform for heavy equipment. Enables autonomous operation of existing mining and construction vehicles.



- **[Teleo](https://teleo.ai/)**  

  Retrofit teleoperation and autonomy system for heavy equipment. Allows remote operation of excavators and loaders from a control center.



- **[Pronto](https://pronto.ai/)**  

  Autonomous haulage system for mining and quarry operations. Features retrofit autonomy for existing truck fleets.



- **[RPMGlobal](https://www.rpmglobal.com/)**  

  Mining software suite including mine planning, scheduling, and fleet management. Features simulation and optimization tools.



## Open-Source GitHub Projects



- **[OpenMines](https://github.com/370025263/openmines)**  

  Light and comprehensive mining simulation environment for truck dispatching (Apache-2.0). **The foundational open-source framework for mine fleet algorithm development and evaluation** . Models the simulation environment from a complex systems perspective with **probabilistic, user-defined events for random event simulation** and multiple evaluation metrics. Provides **six baseline dispatch algorithms**: NaiveDispatcher, RandomDispatcher, NearestDispatcher, FixedGroupDispatcher, SPTFDispatcher, and SQDispatcher . Ships with example mine configurations (North Pit Mine in Holingol, Inner Mongolia with anonymized data). PyPI installable: `pip install openmines`. CLI supports `run` and `visualize` commands generating performance tables and production curves. **The most mature open-source mine dispatch simulator available** .



- **[Mining-Gym](https://github.com/CBCodeHub/Mining-Gym)**  

  Configurable benchmarking environment for optimizing truck dispatch scheduling in open-pit mining using **Reinforcement Learning** (license varies). Built on **Salabim discrete-event simulation** with **Gymnasium-compatible wrapper** . Supports **four classical schedulers** (random, fixed round-robin, shortest-queue-first, min-shovel-wait-time) and **five RL algorithms** (maskable_ppo, ppo, a2c, dqn, trpo). Features fixed test scenarios (A-F), batch evaluation with summary CSVs, and pretrained model playback. Published in Applied Soft Computing (2026) . **The leading open-source RL benchmarking environment for mine dispatch**.



- **[NATURE Stack](https://github.com/goodin-research/nature)**  

  Open-source autonomy stack for **off-road navigation** by wheeled vehicles (license varies). Free and open-source, written in ROS, compatible with **both ROS-1 and ROS-2** . Features modules for **perception, global planning, and local planning** including A*, artificial potential field, spline-based planning, and slope-based obstacle detection . Used by **US Army Engineer Research and Development Center** and provided foundation for **NATO AVT-341 working group** on "Mobility Assessment Methods and Tools for Autonomous Military Ground Systems" . **The only full-stack open-source autonomy software for off-road vehicles** .



- **[Wheel Loader Robot](https://github.com/WfHit/wheel_loader_robot)**  

  Autonomous wheel loader robot system built on **PX4 autopilot framework** (license varies). Features **boom and bucket control** with electric actuator precision, autonomous navigation with path planning and obstacle avoidance, load detection/pickup/placement algorithms, and **dual-mode operation** (manual and VLA auto mode) . Supports Vision-Language-Action (VLA) autonomous control receiving 7-DOF trajectories with smooth interpolation at 50Hz. Hardware configurations for CUAV X7Plus-WL and HKUST NXT-Dual-WL. **The most specialized open-source heavy equipment control system available** .



- **[Autonomous Excavator (MathWorks)](https://github.com/mathworks-robotics/autonomous-excavator)**  

  Virtual testbench for developing and testing autonomous algorithms for heavy offroad vehicles (license varies). Shows how to do **motion planning for an autonomous excavator manipulator arm** using Lidar data generated in Unreal Engine, with closed-loop Simulink/Simscape model and co-simulation visualization . Features Solidworks export workflows using Simscape Multibody Link and URDF exporter. Requires MATLAB 2024a with Simulink, Robotics System Toolbox, Navigation Toolbox, Image Processing Toolbox, Computer Vision Toolbox, and Simscape Multibody .



- **[JKCOM](https://github.com/olivestackscode/jkcom)**  

  AI-powered GPS mapping and perception stack for autonomous electric vehicles (Apache-2.0). Features **multi-sensor fusion** (camera + radar + GPS/IMU), **HD map generation**, real-time localization with GNSS-free fallback, and perception pipeline for object detection, tracking, and free-space segmentation . Compatible with CARLA, NVIDIA Isaac Sim, and ROS 2. Lightweight models suitable for edge deployment. **While designed for EVs, the mapping and localization modules are applicable to mining haul trucks** .



- **[ExT (Excavation Transformer)](https://ar5iv.labs.arxiv.org/html/2509.14992)**  

  Unified framework for large-scale multi-task demonstration generation, pretraining, and fine-tuning of excavator policies (license varies). Demonstrates that **pretrained ExT policies can perform complete excavation workflow zero-shot in sim-to-real setting** . Validates fine-tuning pathways: sft for limited demonstrations, rlft for reward-modeled simulation conditions. **Research-stage but represents the frontier of autonomous excavation learning** .



### Additional Strong Open-Source Options



- **[FusionPlanner](https://ar5iv.labs.arxiv.org/html/2509.14992)** — Multi-task motion planner for mining trucks via multi-sensor fusion. Includes **MiningNav benchmark** (three validation approaches) and **Parallel Mining Simulator (PMS)** for single-truck control and multi-truck scheduling .

- **[ROS2-TMS for Construction](https://github.com/irvs/ros2-tms-for-construction)** — Task management system for construction machinery using open platform OPERA. Field-tested on automated hydraulic excavator .

- **[Aulis (Fraunhofer IML)](https://github.com/fraunhofer-iml/aulis)** — Agent-based open-source operating system for AGV/AMR fleets with **VDA 5050 standard** support. Five modules: order agent, routing agent, optimization module, vehicle agents, and UI module . While designed for intralogistics, the architecture is applicable to mine fleet coordination.

- Community **n8n** workflows for mining fleet alert routing and dispatch automation.



**Frameworks for building custom systems**: Combine **OpenMines** for dispatch algorithm simulation and benchmarking with **Mining-Gym** for RL policy training, **NATURE Stack** for off-road navigation modules, **Wheel Loader Robot** for heavy equipment control patterns, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade mining fleet navigation platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Autonomous mining fleet systems controlling heavy equipment must comply with mining safety regulations (MSHA in US, equivalent authorities globally) and implement rigorous safety validation before deployment.

- **Open-source mining autonomy is simulation-first.** OpenMines and Mining-Gym are **simulation environments** for algorithm development—not production dispatch systems . Deploying learned policies on real equipment requires extensive validation, safety certification, and integration with proven hardware platforms.

- **Off-road autonomy is fundamentally harder than on-road.** NATURE Stack documentation notes: "Autonomous navigation in off-road environments breaks many of the assumptions built into other autonomy algorithms. Without road networks, engineer slopes, and vegetation-free path options, the problem of off-road navigation is more complex and open-ended" .

- **Heavy equipment control requires specialized frameworks.** Wheel Loader Robot's PX4-based system and MathWorks' excavator testbench represent the state of open-source heavy equipment control—but production deployment requires domain expertise, safety systems, and hardware integration .

- Self-hosted open-source solutions require proper security hardening, safety validation, and ongoing maintenance. Mining environments are harsh—equipment must withstand dust, vibration, temperature extremes, and continuous operation.



---



**Made for mining engineers, autonomy researchers, fleet operators, and developers building transparent heavy fleet navigation solutions.**  

Let's make Autonomous Mining Heavy Fleet Navigators more open, data-driven, and safe.
