# Libraries & source code

---
### EvoGym

EvoGym is a simulation platform for evolving the bodies and brains of soft robots-morphology and control. Robots are built from simple blocks called voxels, which can be rigid, soft, or actuated, hence enabling dynamic designs. EvoGym allows these robots to "learn" how to perform tasks like walking or carrying objects using algorithms inspired by evolution and reinforcement learning.

Resources
* [Home Page](https://evolutiongym.github.io/)
* [Install](https://github.com/EvolutionGym/evogym)
* [Tutorials](https://evolutiongym.github.io/tutorials)
* [Demos](https://evolutiongym.github.io/all-tasks)
* [Paper](https://arxiv.org/abs/2201.09863)

---
### SOFA 

[SOFA](https://www.sofa-framework.org/) is an open-source framework designed for interactive mechanical simulations, with a strong focus on bio-mechanics and robotics. It provides advanced constitutive models and algorithms for efficiently computing both soft and rigid body dynamics. SOFA supports linear and non-linear elastic models, offers both explicit and implicit integration schemes, and includes traditional linear solvers. It integrates numerous algorithms and models, making it highly suitable for complex simulation needs in bio-mechanics and robotics.  [Compliance Robotics](https://compliance-robotics.com/) have developed a dedicated graphical user interface (GUI) for SOFA, tailored specifically for robotics applications.

Resources 
* [Home Page](https://softroboticstoolkit.com/sofa)
* [Install](https://www.sofa-framework.org/download/)
* [Tutorials](https://softroboticstoolkit.com/sofa/tutorial)
* [Demos](https://softroboticstoolkit.com/projects)
* [Paper](https://softroboticstoolkit.com/publications/control-elastic-soft-robots-based-real-time-finite-element-method)

---
### SoftZoo
SoftZoo is a soft robot co-design platform for locomotion in diverse environments that supports an extensive, naturally-inspired material set, including the ability to simulate environments such as flat ground, desert, wetland, clay, ice, snow, shallow water, and ocean. SoftZoo provides a variety of tasks relevant for soft robotics, including fast locomotion, agile turning, and path following, as well as differentiable design representations for morphology and control.
With this platform, it is possible to use a wide variety of prevalent representations and co-design algorithms, including control optimization with differentiable physics and reinforcement learning, as well as co-design with evolutionary algorithms.

Resources
* [Home Page](https://sites.google.com/view/softzoo-iclr-2023)
* [Install](https://github.com/zswang666/softzoo)
* [Demos](https://sites.google.com/view/softzoo-iclr-2023/safari)
* [Paper](https://openreview.net/forum?id=Xyme9p1rpZw)

---
### 2D-MR-Sim

2D-MR-Sim (2-dimensional multi-robot simulator) is a framework for experimenting with the evolutionary optimization of 2D simulated robotic agents. It is built on top of [2D-VSR-Sim](https://github.com/ericmedvet/2dhmsr?tab=readme-ov-file), a Java framework for experimenting with a 2D voxel-based soft robots. 2D-MR-Sim provides consistent interfaces for all the voxel-based soft robot (VSR) aspects suitable for optimization and considers by design the presence of sensing, i.e., the possibility of exploiting the feedback from the environment for controlling the VSR. Specifically, 2D-MR-Sim allows one to simulate more kinds of robots (not only Voxel-based Soft Robots, better models the concept of modularity, and is decoupled from the inner physics simulator.

Resources
* [Home Page/Code](https://github.com/ericmedvet/2d-robot-evolution)
* [Paper](https://medvet.inginf.units.it/publications/2020-j-mbds-vsr/)

---
### DisMech
DisMech is a discrete differential geometry-based physical simulator for elastic rod-like structures and soft robots.
Based on the [Discrete Elastic Rods](https://www.cs.columbia.edu/cg/pdfs/143-rods.pdf) framework, it can be used to simulate soft structures for a wide variety of purposes such as robotic deformable material manipulation and soft robot control. DisMech Combines a fully implicit discrete differential geometry-based physics solver with fast and accurate contact handling.

Resources
* [Home Page](https://www.dismech.org/)
* [Install](https://dismech-rods.readthedocs.io/en/latest/install_instructions.html)
* [Docs](https://dismech-rods.readthedocs.io/en/latest/)
* [Code](https://github.com/StructuresComp/dismech-rods)
* [Paper](https://ieeexplore.ieee.org/document/10433745)

---
### Elastica
[Elastica](https://github.com/GazzolaLab/PyElastica) is a simulation environment for simulating assemblies of one-dimensional soft, slender structures using Cosserat rod theory. The theory of Cosserat rods is a method of modeling 1D, slender rods accounting for bend, twist, stretch, and shear; allowing all possible modes of deformation to be considered under a wide range of boundary conditions. It models the rod as a deformable curve with attached deformable vectors to characterize its orientation, and evolves the system using a set of coupled second-order, nonlinear partial differential equations.

Resources
* [Home Page](https://www.cosseratrods.org/)
* [Install](https://github.com/GazzolaLab/PyElastica)
* [Tutorial](https://mybinder.org/v2/gh/GazzolaLab/PyElastica/master?filepath=examples%2FBinder%2F0_PyElastica_Tutorials_Overview.ipynb)
* [Paper](https://ieeexplore.ieee.org/document/9369003)

---
### DiffTaiChi
DiffTaiChi is built on top of [Taichi Lang](https://github.com/yuanming-hu/taichi), an open-source, imperative, parallel programming language for high-performance numerical computation. DiffTaichi significantly boosts the performance and productivity of differentiable physical simulators. DiffTaichi generates gradients of simulation steps using source code transformations that preserve arithmetic intensity and parallelism. A light-weight tape is used to record the whole simulation program structure and replay the gradient kernels in a reversed order, for end-to-end backpropagation.

Resources
* [Home Page/Examples](https://github.com/taichi-dev/difftaichi)
* [Install](https://github.com/yuanming-hu/taichi)
* [Paper](https://arxiv.org/abs/1910.00935)

---
### VoxCraft
VoxCraft is a GPU-accelerated voxel-based physics engine. A voxel is a hollow silicone block that can expand and contract in volume. When multiple voxels are attached together they become a robot: a voxelbot. VoxCraft allows you to test robot designs before constructing them in real life. 

Resources
* [Home Page](https://voxcraft.github.io/)
* [Install](https://github.com/voxcraft/voxcraft-sim)
* [Documentation](https://voxcraft.readthedocs.io/en/latest/)
