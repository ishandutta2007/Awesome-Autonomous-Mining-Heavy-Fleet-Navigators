# Awesome-Autonomous-Mining-Heavy-Fleet-Navigators

## Top Autonomous Mining Heavy Fleet Navigators Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Autonomous Haulage, Fleet Dispatch & Unmanned Excavation*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Mining Heavy Fleet Navigators**. These tools enable mining operators to coordinate autonomous haul trucks, excavators, and loaders in harsh environments—optimizing dispatch, reducing fuel consumption, and improving safety through deterministic fleet algorithms.



**Examples** include Caterpillar MineStar, Komatsu FrontRunner, Hexagon Mining, Sandvik AutoMine, Epiroc Mobius, ASI Mining, SafeAI, Teleo, Pronto, and RPMGlobal (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, open mine simulation, and transparent dispatch algorithm development—ideal for mining engineers, researchers, and developers seeking vendor-independent fleet automation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Sector Overview & Market Dynamics

The global autonomous mining equipment and fleet navigation sector is valued at approximately **$4.5B to $5.0B** and projected to surpass **$11B to $15B+** by the early 2030s (CAGR of ~11%). The market exhibits a **bifurcated concentration**: the physical heavy-machinery and ultra-class vehicle layer is **highly concentrated** among global legacy OEMs (Caterpillar, Komatsu, Sandvik, Epiroc), whereas the autonomy perception software, retrofit navigation kits, and interoperable fleet dispatch layer is **moderately fragmented**, driving consolidation and venture-backed innovation.

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Company Scale (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier Limits / Evaluation | Overview & Focus |
| :--- | :--- | :--- | :--- | :--- |
| **[Caterpillar MineStar](https://www.cat.com/en_US/by-industry/mining/surface-mining/surface-technology.html)** | $67.6B annual revenue (Caterpillar Inc.) | Starting at ~$15,000/site/year (entry-level MineStar Edge fleet tracking; scales up for Command AHS) | No permanent free tier; 30-day dealer-facilitated on-site pilot trial kits available upon qualification | Flagship mining ecosystem with Command (haulage), Fleet (dispatch), and Health (diagnostics) managing the world's largest autonomous truck fleet. |
| **[Komatsu FrontRunner](https://www.komatsu.com/en/solutions/mining/autonomous-haulage/)** | ~$26.5B (¥4.13T) annual revenue (Komatsu Ltd.) | Starting at ~$50,000/site base deployment license (scales with fleet size & network dispatch) | No permanent free tier; 30-to-60 day controlled site proof-of-concept (PoC) trial on select mine testbeds | Autonomous haulage system (AHS) with extensive open-pit deployments globally, featuring high-precision GNSS and obstacle avoidance. |
| **[Sandvik AutoMine](https://www.rocktechnology.sandvik/en/products/automation/automine/)** | ~$12.8B (SEK 120.7B) annual revenue (Sandvik AB) | Starting at ~$25,000 baseline software deployment (AutoMine Lite / Tele-Remote entry tier) | No permanent free tier; 30-day simulation & hardware testbed pilot evaluation for certified mine operators | Underground loaders and trucks automation suite enabling autonomous navigation and remote control from surface operations rooms. |
| **[Epiroc Mobius](https://www.epiroc.com/en-us/products/automation/mobius)** | ~$5.8B (SEK 60B+) annual revenue (Epiroc AB) | Starting at ~$20,000/year base server platform license (Mobius Core dispatch & fleet tracking) | No permanent free tier; 30-day interactive simulation environment sandbox demo upon enterprise verification | Mixed-fleet automation and traffic management platform for underground and surface drilling and haulage operations. |
| **[Hexagon Mining](https://hexagon.com/industries/mining)** | ~$4.0B (€3.7B) annual revenue (Hexagon AB) | Starting at ~$12,000/year (entry MinePlan & OP Pro fleet management single-seat module) | No permanent free tier; 14-day full-feature trial for select planning software modules | Comprehensive digital mining platform combining autonomous drilling, fleet dispatch, collision avoidance, and spatial analytics. |
| **[Pronto](https://pronto.ai/)** | ~$1.7B parent valuation (Acquired by Atoms, $1.7B Series A) | Starting at ~$5,000/vehicle/month (Autonomous Haulage System retrofit subscription) | No permanent free tier; 14-day field demonstration & pilot benchmark period on active quarry haul routes | Sensor-driven retrofit autonomy suite for production haulage in quarry and mining fleets, eliminating reliance on extensive fixed infrastructure. |
| **[RPMGlobal](https://www.rpmglobal.com/)** | $681M acquisition valuation (Acquired by Caterpillar; ~$50M+ ARR) | Starting at ~$10,000/year per workstation/module license (AMT Asset Management / Schedule modules) | No permanent free tier; 30-day guided enterprise evaluation license (educational partners get free semester lab licenses) | Mining software enterprise suite delivering short- and long-term mine planning, fleet simulation, and maintenance scheduling. |
| **[ASI Mining](https://www.asimining.com/)** | ~$225M parent funding (SoftBank) / ~$30M pre-acquisition revenue | Starting at ~$8,000/vehicle/month base autonomy kit & Mobius-integrated software license | No permanent free tier; 30-day structured proof-of-concept site simulation trial for commercial fleet operators | OEM-agnostic autonomous conversion kits (Mobius Core) for retrofitting haul trucks, excavators, and ancillary vehicles. |
| **[SafeAI](https://safeai.com/)** | ~$150M historical valuation ($91M funding; merged with Pronto) | Starting at ~$6,500/vehicle/month autonomy software subscription tier | No permanent free tier; 30-day monitored site demonstration and deployment trial on partner machinery | Heavy equipment retrofit autonomy platform automating mixed hauling and loading fleets for open-pit mining and construction. |
| **[Teleo](https://teleo.ai/)** | ~$60M valuation ($29.8M venture funding) | Starting at ~$3,500/month per operator station / vehicle kit subscription | No permanent free tier; 14-day on-site equipment teleoperation pilot trial for qualified construction & mining contractors | Supervised autonomy and high-precision remote operation system allowing centralized control of excavators and wheel loaders. |



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
