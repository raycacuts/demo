# demo
# Physics-Based Character Control with DeepMimic Extensions

This project builds on [DeepMimic](https://github.com/xbpeng/DeepMimic), a reinforcement learning framework for physics-based character animation.  
My research extends DeepMimic to achieve robust locomotion and goal-directed navigation using hierarchical control.

## Overview

- **Low-Level Controller (LLC)**  
  A motion imitation controller trained with DeepMimic to produce stable and realistic physics-based locomotion from movement vectors.

- **High-Level Controller (HLC)**  
  A navigation policy that directs agents toward target locations by providing movement vectors to the LLC.

- **Scenarios**  
  The system is tested across a variety of environments and objectives to evaluate adaptability and stability.

## Demo Videos

- **LLC Demonstrations**
  - [`llc_box.mp4`](link) — Box-shaped agent locomotion  
  - [`llc_humanoid.mp4`](link) — Humanoid agent locomotion

- **HLC Demonstrations**
  - [`hlc.mp4`](link) — High-level navigation towards target goals

- **Test Scenarios**
  - [`circle.mp4`](link) — Circular navigation test  
  - [`scenarios.mp4`](link) — Multiple scenario evaluations

*(If GitHub cannot host large files, the videos are available via external links.)*

## Features

- Physics-based locomotion from motion capture imitation  
- Hierarchical control with decoupled high-level navigation and low-level locomotion  
- Support for multiple agent morphologies (box, humanoid, etc.)  
- Tested in diverse scenarios for robustness and generalization

## Built With

- [DeepMimic](https://github.com/xbpeng/DeepMimic)  
- [Bullet Physics](https://github.com/bulletphysics/bullet3)  
- Python (for training and control logic)  
- C++ (for physics simulation)

---

## Citation

If referencing this project in research, please cite [DeepMimic](https://xbpeng.github.io/projects/DeepMimic/index.html) as the base framework.

