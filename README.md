# ForestEye-Edge-AI-Poaching-Detection

## Overview
ForestEye is a multi-modal edge AI system designed to detect potential poaching activity using vision and audio inputs in real-time environments.

The system focuses on low-power, event-driven sensing combined with intelligent threat classification.

---

## Problem
Poaching detection in forest areas is often delayed and reactive. Traditional surveillance systems generate high false positives and require constant monitoring.

---

## Solution
ForestEye introduces:
- Event-driven sensing using PIR sensors and sound sensors
- Multi-modal detection (vision + audio)
- Multi-frame validation to reduce false positives
- Zone-aware decision logic

---

## System Architecture
- ESP32 nodes for sensing
- Raspberry Pi for central processing
- Vision pipeline:
  - Person Detection
  - Pose Estimation
  - Threat Classification
- Audio pipeline:
  - CNN-based sound classification

---

## Current Implementation
- Vision pipeline implemented using laptop camera input
- Pose detection and threat classification tested in software
- Audio model explored for gunshot detection
- Hardware prototype attempted but faced sensor reliability issues

---

## Challenges
- Sensor inconsistency during real-world testing
- Balancing accuracy with low-power constraints
- Integration between hardware and ML models

---

## Future Work
- Improve hardware reliability
- Optimize models for edge deployment
- Real-time multi-node communication

---

## Tech Stack
- Python
- OpenCV / ML models
- ESP32, Raspberry Pi (planned hardware)
