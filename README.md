# Formula-Style RC Car: Design, Telemetry & Traction Control

Two University of Guelph engineering students designing, building and testing
a 1:10-scale Formula-style electric RC car.

## Goal
Answer one engineering question: **how fast can the car accelerate, what limits it,
and can we improve it?**

1. **Predict, then measure:** model acceleration from first principles, then compare
   to logged sensor data.
2. **Break it, redesign it:** load-test a known weak part to failure, redesign it in
   Fusion (with FEA), and prove the improvement.
3. **Traction control (stretch):** detect rear-wheel slip and reduce throttle;
   compare runs with it on vs off.

## What's original vs borrowed
| Borrowed | Ours |
|---|---|
| Base car: [OpenRC F1 by Daniel Norée](http://danielnoree.com/the-openrc-f1-build-guide/) | Chassis tub, electronics bay, sensor mounts |
| | Redesigned weak parts, PCB, firmware, tests |

## Tech
Fusion (CAD/FEA) · Arduino Nano ESP32 (C++) · KiCad (PCB) · Hall-effect wheel-speed
sensors · IMU · SD data logging

## Repo layout
- `logbook/`: dated entries, who did what
- `cad/`: Fusion exports, drawings
- `firmware/`: Arduino code
- `electronics/`: wiring, PCB
- `tests/`: data and graphs

## Progress
- [x] Project planned, parts researched (Nov 2026)
- [ ] Stock car printed and driving
- [ ] Custom chassis + data logging
- [ ] Custom PCB
- [ ] Testing and traction control
- [ ] Final report and video
