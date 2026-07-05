# Humanoid SDK

**Version:** 0.1 Draft

The Humanoid SDK defines the developer interface for applications executing on Humanoid OS.

Rather than issuing low-level motor commands, applications request high-level humanoid capabilities.

---

## Example APIs

RequestWalk()

RequestStand()

RequestReach()

RequestGrasp()

RequestLift()

RequestCarry()

RequestToolUse()

RequestHumanContact()

RequestMissionAuthority()

RequestReleaseToken()

---

## Design Goals

- Stable developer APIs
- Hardware abstraction
- Constitution-aware execution
- Whole-body coordination
- Capability-based programming

---

## Relationship

Applications

↓

Humanoid SDK

↓

Humanoid Runtime

↓

Humanoid Operating System

---

## Status

Draft

Version 0.1

---

## Future Work

- Python SDK
- C++ SDK
- ROS2 bindings
- Rust SDK
- Reference examples
