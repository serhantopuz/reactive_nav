# reactive_nav

Reactive navigation for a differential-drive robot in ROS 2 — no map, no global planner.

**Status:** in development.

A Bug2 state machine that reaches a goal using only local laser scans, built to learn ROS 2 properly: custom messages and actions, parameters, launch files, tf2, and integration tests that run headless.

## Stack

- ROS 2 Jazzy · C++17 · Python 3.12 · Gazebo Harmonic
- rosidl · tf2 · rosbag2 · launch_testing · pytest

## Roadmap

- [ ] Laser-scan safety monitor node; pub/sub, params, launch, tf2, rosbag2
- [ ] Bug2 as a state machine (Python)
- [ ] Hot loop ported to C++; action server for go-to-(x, y); headless integration tests

## License

Apache-2.0
