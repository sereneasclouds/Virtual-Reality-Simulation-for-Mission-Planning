# Virtual Reality Simulation of Homing Missile System for Mission Planning — RQ-180 Drone

A Unity3D-based Virtual Reality simulation developed as a group academic
project at Manipal Institute of Technology to study UAV flight behaviour,
target identification, missile guidance, weapon-target assignment, and
mission planning in a controlled virtual environment.

The simulation provides an interactive environment for simulating different
mission scenarios and studying the interaction between pilot/operator inputs,
UAV behaviour, target tracking, weapon selection, missile guidance, and
engagement outcomes.

---

##  Project Overview

The project presents a Virtual Reality simulation of an RQ-180 UAV equipped
with multiple missile profiles.

The system integrates:

- UAV flight dynamics
- Manual and autonomous UAV control
- Real-time player inputs
- Target detection and tracking
- Target classification
- Target locking
- Weapon and missile management
- Multiple missile guidance behaviours
- Multi-target engagement
- Missile-target assignment
- Collision and damage handling
- HUD-based flight and targeting information
- Mission outcome feedback

The simulation was developed in **Unity3D using C#** with a modular
architecture that separates flight control, targeting, weapon management,
missile behaviour, and user-interface components.

---

##  Project Objectives

The primary objectives of the project are to:

- Simulate different mission scenarios in a controlled VR environment.
- Provide an interactive environment for understanding UAV and weapon-system
  behaviour.
- Study the relationship between operator inputs and system outputs.
- Visualize target detection, tracking, locking, and engagement processes.
- Demonstrate different missile flight and guidance profiles.
- Explore multi-target engagement and weapon-target assignment.
- Provide a safe and repeatable environment for training and experimentation.
- Support pilot/operator understanding of system responses under different
  mission conditions.
- Reduce dependence on expensive and hazardous live training environments.
- Support more efficient mission planning by allowing scenarios to be
  repeatedly simulated and evaluated.
- Provide feedback through HUD telemetry and engagement-status indicators.

---

##  Applications

The simulation can be used as a controlled virtual environment for:

### 1. Mission Scenario Simulation

Different mission scenarios can be recreated and evaluated in a VR
environment, including static targets, moving ground targets, aerial targets,
and multiple simultaneous targets.

### 2. Pilot / Operator Training

The simulation provides an interactive environment in which users can practice
flight control, target acquisition, target locking, weapon selection, and
engagement procedures without requiring physical aircraft or live-fire
exercises.

### 3. Understanding Input–Output Behaviour

The system allows users to observe how operator inputs affect UAV behaviour,
targeting, missile launch sequences, and engagement outcomes.

Examples include:

- Flight-control inputs → UAV movement
- Target detection → HUD indication
- Target lock → weapon readiness
- Fire command → missile launch sequence
- Target movement → missile guidance response
- Missile impact → target damage and mission feedback

### 4. Training and Error Reduction

A repeatable virtual environment allows users to practice complex scenarios
and understand system behaviour before performing equivalent procedures in
higher-risk environments.

Repeated simulation can help users identify procedural errors and improve
familiarity with system interactions.

### 5. Mission Planning

The simulation can be used to study weapon-target assignment, engagement
timing, target prioritization, and multi-target coordination within a
controlled environment.

### 6. Scenario Testing

Different target positions, target movements, missile profiles, and
engagement configurations can be tested without modifying physical hardware
or conducting live exercises.

---

##  System Architecture

The simulation follows a modular architecture consisting of interconnected
subsystems.

```text
                    RQ-180 VR SIMULATION
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
   UAV / Player       Targeting &        UI / HUD
      Control           Tracking
          │                 │                 │
          └─────────────────┼─────────────────┘
                            │
                            ▼
                   Weapon Management
                            │
                            ▼
                    Missile Guidance
                            │
                            ▼
                  Impact / Damage System
                            │
                            ▼
                   Mission Feedback
