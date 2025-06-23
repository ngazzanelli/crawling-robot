# Learning to crawl 

A real-time, physics-based simulator for a crawling robot trained with reinforcement learning.

## 📚 Overview

This project was developed as part of a master's-level Real-Time Systems course in Robotics and Automation Engineering at the University of Pisa. The simulator features a two-joint crawling robot learning to move forward using Q-learning, all within a real-time scheduling environment on Linux.

The project explores the intersection of control theory, dynamics, and concurrency, integrating:

- Lyapunov-based nonlinear control
- Real-time task scheduling using POSIX threads (`pthread`)
- A physical simulation with symbolic dynamics
- Q-learning with visual feedback
- Custom graphics using Allegro library

## ⚙️ Technologies Used

- **Language**: C
- **Concurrency**: POSIX threads (`pthread`)
- **Graphics**: Allegro 4
- **Math Tools**: Mathematica (for dynamics modeling)
- **Control**: Lyapunov-based backstepping control
- **OS**: Linux

## 🧠 Key Features

- **Real-time architecture**: Four periodic tasks (simulation, learning, UI, graphics) with explicit deadline management.
- **Q-learning agent**: Learns optimal joint-angle actions to produce forward motion.
- **Dynamic simulation**: Includes full kinematic and dynamic modeling using Lagrangian mechanics.
- **User interface**: Interactive GUI allows live tuning of learning parameters and observing robot state and rewards.

## 🚀 Getting Started

### Prerequisites

- Linux OS
- `gcc`
- Allegro 4 development libraries

### Build and Run

```bash
make
./crawling_robot
```
### Controls 
Todo
