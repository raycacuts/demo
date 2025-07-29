# Physics-Based Character Control with DeepMimic Extensions

This project builds on [DeepLoco](https://xbpeng.github.io/projects/DeepLoco/index.html), a reinforcement learning framework for physics-based character animation.  
My research extends DeepLoco to achieve more generalized and robust locomotion and goal-directed navigation using hierarchical control.

## Overview

- **Low-Level Controller (LLC)**  
  A motion imitation controller trained to produce stable and realistic physics-based locomotion from movement vectors.

- **High-Level Controller (HLC)**  
  A navigation policy that directs agents toward target locations by providing movement vectors to the LLC.

- **Scenarios**  
  The system is tested across a variety of environments and objectives to evaluate adaptability and stability.

## Demo Videos

### LLC Demonstrations
[![LLC Box Demo](https://img.youtube.com/vi/PSGnDfQTj3g/0.jpg)](https://www.youtube.com/watch?v=PSGnDfQTj3g)  
[![LLC Humanoid Demo](https://img.youtube.com/vi/U1S0KrvUdaU/0.jpg)](https://www.youtube.com/watch?v=U1S0KrvUdaU)

### HLC Demonstrations
[![HLC Navigation Demo](https://img.youtube.com/vi/jfo7rZhpixc/0.jpg)](https://www.youtube.com/watch?v=jfo7rZhpixc)

### Test Scenarios
[![Circle Scenario Demo](https://img.youtube.com/vi/fXfoR93CYf4/0.jpg)](https://www.youtube.com/watch?v=fXfoR93CYf4)  
[![Multiple Scenarios Demo](https://img.youtube.com/vi/7ydab6GlBX0/0.jpg)](https://www.youtube.com/watch?v=7ydab6GlBX0)


## Features

- Physics-based locomotion from motion capture imitation  
- Hierarchical control with decoupled high-level navigation and low-level locomotion  
- Support for multiple agent morphologies (box, humanoid, etc.)  
- Tested in diverse scenarios for robustness and generalization

## Built With

- [DeepLoco](https://xbpeng.github.io/projects/DeepLoco/index.html)  
- [Bullet Physics](https://github.com/bulletphysics/bullet3)  
- Python (for training and control logic)  
- C++ (for physics simulation)


