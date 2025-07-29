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

### LLC Demonstrations
[![LLC Box Demo](https://img.youtube.com/vi/PSGnDfQTj3g/0.jpg)](https://www.youtube.com/watch?v=PSGnDfQTj3g)

[![LLC Humanoid Demo](https://img.youtube.com/vi/YOUR_HUMANOID_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_HUMANOID_VIDEO_ID)

### HLC Demonstrations
[![HLC Navigation Demo](https://img.youtube.com/vi/YOUR_HLC_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_HLC_VIDEO_ID)

### Test Scenarios
[![Circle Scenario Demo](https://img.youtube.com/vi/YOUR_CIRCLE_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_CIRCLE_VIDEO_ID)  
[![Multiple Scenarios Demo](https://img.youtube.com/vi/YOUR_SCENARIOS_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_SCENARIOS_VIDEO_ID)

*(Click the images above to watch the videos on YouTube.)*

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
