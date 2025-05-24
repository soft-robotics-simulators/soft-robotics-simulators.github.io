# Libraries & Source Code

## Contents
1. [2D-MR-Sim](#2D-MR-Sim)
2. [DiffPD](#DiffPD)
3. [DiffTaiChi](#DiffTaiChi) 
4. [DiffVineSim](#DiffVineSim)
5. [DisMech](#DisMech)
6. [Elastica](#Elastica)
7. [EvoGym](#EvoGym)
8. [GradSim](#GradSim)
9. [IPC](#IPC)
11. [SOFA](#SOFA)
12. [SoftZoo](#SoftZoo)
13. [SoMo](#SoMo)
14. [Warp](#Warp)
15. [VoxCraft](#VoxCraft)

---
### 2D-MR-Sim <a name="2D-MR-Sim"></a>

2D-MR-Sim (2-dimensional multi-robot simulator) is a framework for experimenting with the evolutionary optimization of 2D simulated robotic agents. It is built on top of [2D-VSR-Sim](https://github.com/ericmedvet/2dhmsr?tab=readme-ov-file), a Java framework for experimenting with a 2D voxel-based soft robots. 2D-MR-Sim provides consistent interfaces for all the voxel-based soft robot (VSR) aspects suitable for optimization and considers by design the presence of sensing, i.e., the possibility of exploiting the feedback from the environment for controlling the VSR. Specifically, 2D-MR-Sim allows one to simulate more kinds of robots (not only Voxel-based Soft Robots, better models the concept of modularity, and is decoupled from the inner physics simulator.

Resources
* [Home Page/Code](https://github.com/ericmedvet/2d-robot-evolution)
* [Paper](https://medvet.inginf.units.it/publications/2020-j-mbds-vsr/)

---
### DiffPD <a name="DiffPD"></a>
DiffPD (Differentiable Projective Dynamics) is a differentiable soft-body simulator intended for learning and control applications. Optimized for speed, DiffPD uses implicit time integration with projective dynamics (PD) and exploits a pre-factorized Cholesky decomposition to speed up backpropagation. Thus, DiffPD can prioritize speed while still managing a small sim2real gap.

Resources
* [Home Page](https://diffpd.csail.mit.edu/)
* [Install](https://github.com/mit-gfx/diff_pd_public)
* [Paper](https://dl.acm.org/doi/full/10.1145/3490168)

---
### DiffTaiChi <a name="DiffTaiChi"></a>
DiffTaiChi is built on top of [Taichi Lang](https://github.com/yuanming-hu/taichi), an open-source, imperative, parallel programming language for high-performance numerical computation. DiffTaichi significantly boosts the performance and productivity of differentiable physical simulators. DiffTaichi generates gradients of simulation steps using source code transformations that preserve arithmetic intensity and parallelism. A light-weight tape is used to record the whole simulation program structure and replay the gradient kernels in a reversed order, for end-to-end backpropagation.

Resources
* [Home Page/Examples](https://github.com/taichi-dev/difftaichi)
* [Install](https://github.com/yuanming-hu/taichi)
* [Demos](https://somo.readthedocs.io/en/latest/examples/index.html)
* [Paper](https://arxiv.org/abs/1910.00935)

---
### DiffVineSim <a name="DiffVineSim"></a>
DiffVineSim (Differentiable Vine Simulator) is a differentiable forward-dynamics simulator for an extendable, soft vine robot. Occupying a promising niche in the field of soft robotics, soft-growing robots such as vine robots allow for navigation and growth in tightly confined environments. DiffVineSim presents a differentiable approach to vine robot simulation, with more complex parameter fitting and multiple simultaneous rollouts.

Resources
* [Install](https://github.com/CoMMALab/DiffVineSimPy)
* [Paper](https://arxiv.org/abs/2501.17963)

---
### DisMech <a name="DisMech"></a>
DisMech is a discrete differential geometry-based physical simulator for elastic rod-like structures and soft robots.
Based on the [Discrete Elastic Rods](https://www.cs.columbia.edu/cg/pdfs/143-rods.pdf) framework, it can be used to simulate soft structures for a wide variety of purposes such as robotic deformable material manipulation and soft robot control. DisMech Combines a fully implicit discrete differential geometry-based physics solver with fast and accurate contact handling.

Resources
* [Home Page](https://www.dismech.org/)
* [Install](https://dismech-rods.readthedocs.io/en/latest/install_instructions.html)
* [Docs](https://dismech-rods.readthedocs.io/en/latest/)
* [Code](https://github.com/StructuresComp/dismech-rods)
* [Paper](https://ieeexplore.ieee.org/document/10433745)

---
### Elastica <a name="Elastica"></a>
[Elastica](https://github.com/GazzolaLab/PyElastica) is a simulation environment for simulating assemblies of one-dimensional soft, slender structures using Cosserat rod theory. The theory of Cosserat rods is a method of modeling 1D, slender rods accounting for bend, twist, stretch, and shear; allowing all possible modes of deformation to be considered under a wide range of boundary conditions. It models the rod as a deformable curve with attached deformable vectors to characterize its orientation, and evolves the system using a set of coupled second-order, nonlinear partial differential equations.

Resources
* [Home Page](https://www.cosseratrods.org/)
* [Install](https://github.com/GazzolaLab/PyElastica)
* [Tutorial](https://mybinder.org/v2/gh/GazzolaLab/PyElastica/master?filepath=examples%2FBinder%2F0_PyElastica_Tutorials_Overview.ipynb)
* [Paper](https://ieeexplore.ieee.org/document/9369003)

---
### EvoGym <a name="EvoGym"></a>

EvoGym is a simulation platform for evolving the bodies and brains of soft robots-morphology and control. Robots are built from simple blocks called voxels, which can be rigid, soft, or actuated, hence enabling dynamic designs. EvoGym allows these robots to "learn" how to perform tasks like walking or carrying objects using algorithms inspired by evolution and reinforcement learning.

Resources
* [Home Page](https://evolutiongym.github.io/)
* [Install](https://github.com/EvolutionGym/evogym)
* [Tutorials](https://evolutiongym.github.io/tutorials)
* [Demos](https://evolutiongym.github.io/all-tasks)
* [Paper](https://arxiv.org/abs/2201.09863)

---
### GradSim <a name="GradSim"></a>
GradSim focuses on the problem of estimating an object’s physical properties such as mass, friction, and elasticity directly from video sequences. This framework overcomes the dependence on 3D supervision by leveraging differentiable multiphysics simulation and differentiable rendering to jointly model the evolution of scene dynamics and image formation. By modeling the process by which physical objects map to pixels in a video, GradSim enables learning in challenging visuomotor control tasks, without relying on state-based (3D) supervision, while obtaining performance competitive to or better than techniques that rely on precise 3D labels.

Resources
* [Home Page](https://gradsim.github.io/)
* [Install](https://github.com/gradsim/gradsim)
* [Demo](https://openreview.net/pdf?id=c_E8kFWfhp0)
* [Paper](https://openreview.net/pdf?id=c_E8kFWfhp0)

---
### Sim <a name="IPC"></a>
IPC (Incremental Potential Contact) is a simulator which focuses on variationally solving implicitly time-stepped nonlinear elastodynamics. By allowing the user to select accuracy tolerances, desired accuracies for a simulation’s dynamics and geometry may be decoupled. Employing an implicit time-stepping method, the custom nonlinear solver addresses contact problems that are intersectionfree, inversion-free, and accurate, with speeds comparable to or faster than available methods that lack both convergence and feasibility. 

Resources
* [Home Page/Examples](https://ipc-sim.github.io/)
* [Install](https://github.com/ipc-sim/IPC)
* [Docs](https://github.com/ipc-sim/IPC/wiki)
* [Paper](https://ipc-sim.github.io/file/IPC-paper-fullRes.pdf)

---
### SOFA <a name="SOFA"></a>

[SOFA](https://www.sofa-framework.org/) is an open-source framework designed for interactive mechanical simulations, with a strong focus on bio-mechanics and robotics. It provides advanced constitutive models and algorithms for efficiently computing both soft and rigid body dynamics. SOFA supports linear and non-linear elastic models, offers both explicit and implicit integration schemes, and includes traditional linear solvers. It integrates numerous algorithms and models, making it highly suitable for complex simulation needs in bio-mechanics and robotics.  [Compliance Robotics](https://compliance-robotics.com/) have developed a dedicated graphical user interface (GUI) for SOFA, tailored specifically for robotics applications.

Resources 
* [Home Page](https://softroboticstoolkit.com/sofa)
* [Install](https://www.sofa-framework.org/download/)
* [Tutorials](https://softroboticstoolkit.com/sofa/tutorial)
* [Demos](https://softroboticstoolkit.com/projects)
* [Paper](https://softroboticstoolkit.com/publications/control-elastic-soft-robots-based-real-time-finite-element-method)

---
### SoftZoo <a name="SoftZoo"></a>
SoftZoo is a soft robot co-design platform for locomotion in diverse environments that supports an extensive, naturally-inspired material set, including the ability to simulate environments such as flat ground, desert, wetland, clay, ice, snow, shallow water, and ocean. SoftZoo provides a variety of tasks relevant for soft robotics, including fast locomotion, agile turning, and path following, as well as differentiable design representations for morphology and control.
With this platform, it is possible to use a wide variety of prevalent representations and co-design algorithms, including control optimization with differentiable physics and reinforcement learning, as well as co-design with evolutionary algorithms.

Resources
* [Home Page](https://sites.google.com/view/softzoo-iclr-2023)
* [Install](https://github.com/zswang666/softzoo)
* [Demos](https://sites.google.com/view/softzoo-iclr-2023/safari)
* [Paper](https://openreview.net/forum?id=Xyme9p1rpZw)

---
### SoMo <a name="SoMo"></a>
SoMo (**So**ft**Mo**tion) is a framework to facilitate the simulation of continuum manipulator (CM) motion in [pybullet](https://github.com/bulletphysics/bullet3/tree/master/examples/pybullet). In SoMo, continuum manipulators are approximated as a series of rigid links connected by spring-loaded joints. SoMo makes it easy to create URDFs of such approximated manipulators and load them into pybullet's rigid body simulator. With SoMo, environments with various continuum manipulators, such as hands with soft fingers (xxx links), or snakes, can be created and controlled with only a few lines of code.

Resources
* [Home Page/Examples](https://somo.readthedocs.io/en/latest/)
* [Install](https://github.com/GrauleM/somo)
* [Paper](https://dl.acm.org/doi/10.1109/IROS51168.2021.9636059)

---
### Warp <a name="Warp"></a>
NVIDIA Warp is a Python framework for writing high-performance simulation and graphics code. Warp takes regular Python functions and JIT compiles them to efficient kernel code that can run on the CPU or GPU. Warp is designed for spatial computing and comes with a rich set of primitives that make it easy to write programs for physics simulation, perception, robotics, and geometry processing. In addition, Warp kernels are differentiable and can be used as part of machine-learning pipelines with frameworks such as PyTorch, JAX and Paddle.

Resources
* [Home Page](https://developer.nvidia.com/warp-python)
* [Install](https://github.com/NVIDIA/warp)
* [Docs](https://nvidia.github.io/warp/)

---
### VoxCraft <a name="VoxCraft"></a>
VoxCraft is a GPU-accelerated voxel-based physics engine. A voxel is a hollow silicone block that can expand and contract in volume. When multiple voxels are attached together they become a robot: a voxelbot. VoxCraft allows you to test robot designs before constructing them in real life. 

Resources
* [Home Page](https://voxcraft.github.io/)
* [Install](https://github.com/voxcraft/voxcraft-sim)
* [Documentation](https://voxcraft.readthedocs.io/en/latest/)
