# Max Bingham Nikol

Mechanical Engineering student at the Technical University of Munich focused
on robotics, autonomous vehicles, and LiDAR perception.

Research Assistant at the TUM Chair of Automotive Technology, working on
autonomous-vehicle systems. My bachelor's thesis investigates how simulated
weather faults affect LiDAR odometry.

[LinkedIn](https://www.linkedin.com/in/mjbinghamnikol) · Munich, Germany

---

## Selected robotics work

### [Feedbot — autonomous SO-101 manipulation](https://github.com/MaxBingham/RoboticsHackCal)

Weekend team project that trained and deployed an ACT policy for an autonomous
peanut handoff on a physical SO-101 arm. My work covered the SO-101/SmolVLA
integration, checkpoint joint-unit correction, safety-gated runner, and ACT
launch bridge. Includes the hardware video and exact rollout configuration.

**Python · LeRobot · ACT · SO-101 · ElevenLabs**

### [LiDAR weather-fault injection for odometry](https://github.com/MaxBingham/LiDAR_Odometry_FaultInjection_Thesis)

Bachelor's-thesis pipeline for injecting simulated fog and rain into KITTI
scans as they enter KISS-ICP, then evaluating odometry robustness with EVO
APE/RPE metrics. Includes parameter sweeps, portable injector tests, and clear
separation between fault injection and fault detection.

**Python · NumPy · KISS-ICP · KITTI · EVO · point clouds**

### [Franka Panda RGB-D sorting environment](https://github.com/MaxBingham/Simulation-Scene-Setup)

Built a MuJoCo/Gymnasium environment and labeled RGB-D data generator for a
simulated fulfillment station. Provides seeded object randomization,
proprioceptive and camera observations, privileged pose labels, and a
reproducible smoke test. The repository is simulation infrastructure, not a
trained sorting controller.

**Python · MuJoCo · Gymnasium · RGB-D · simulation**

---

## Technical focus

- **Robotics:** manipulation, robot learning, simulation, sensor integration
- **Autonomous systems:** LiDAR odometry, point-cloud processing, robustness evaluation
- **Languages and tools:** Python, C++, Linux, Git, Docker, ROS
