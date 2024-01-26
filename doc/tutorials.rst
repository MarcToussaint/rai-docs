=========
Tutorials
=========

All tutorials are jupyter notebooks, downloadable from https://github.com/MarcToussaint/rai-tutorials. For installation instructions, see `Getting Started <getting_started.html>`_.

The first 3 are **intro tutorials** that introduce essentials for understanding the code:

* **Configurations**: The core data structure used to represent scenes and robots, compute features, and feed into optimization problems, simulations, and real robot control.
* **BotOp**: The *Robot Operation* interface used to control a real or simulated robot, as well as to access sensor.
* **KOMO**: A framework to formulate optimization problems, esp. for motion design (IK, path optimization, and manipulation planning).

.. toctree::
   :glob:
   :maxdepth: 1

   tutorials/config_1_intro
   tutorials/botop_1_intro
   tutorials/komo_1_intro

The remaining tutorials cover various topics in more depth:

.. toctree::
   :glob:
   :maxdepth: 1

   tutorials/botop_2_real_robot
   tutorials/config_2_features
   tutorials/config_3_import_edit
   tutorials/komo_2_reporting
   tutorials/komo_3_manipulation
   tutorials/intf_physx_simulation
   tutorials/intf_rendering
   tutorials/intf_rrt
   tutorials/intf_nlp_solvers
   tutorials/intf_gym_environment
   
