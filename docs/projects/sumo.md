# Sumo Robot

<span class="pill">DOCUMENTATION DRAFT</span>

## Project overview

A Sumo Robot is designed to detect an opponent and maneuver inside a competition ring. This page is a **documentation starter** for an existing team project; implementation details need confirmation.

## Project details

| Field | Value |
| --- | --- |
| Project owner | To be assigned |
| Status | Hardware/software inventory pending |
| Controller | To be verified |
| Motor driver | To be verified |
| Sensors | To be verified |
| Code repository | To be linked |

## System architecture (conceptual)

```text
Sensors ──> Microcontroller ──> Motor Driver ──> Motors
                 │
             Control Logic
```

## Hardware checklist

- [ ] Record actual controller model
- [ ] Record motor driver and motor specifications
- [ ] Record edge/opponent sensors
- [ ] Record battery chemistry, voltage, and power protection
- [ ] Add clear wiring diagram and labeled photos

## Software and setup

1. Identify the firmware language and required IDE.
2. Link the actual source code repository.
3. Document board settings, dependencies, and pin assignments.
4. Record upload procedure and safe test conditions.

## Test plan

| Test | Expected behavior | Actual result |
| --- | --- | --- |
| Startup | Safe initialization | Pending |
| Edge detection | Avoid leaving the ring | Pending |
| Opponent detection | Respond to opponent | Pending |
| Motor direction | Move as commanded | Pending |

## Known issues and improvements

To be completed after the team's hardware and firmware are reviewed.

!!! warning "Safety"
    Test motors with wheels lifted or the robot secured first. Verify battery polarity and current limits before powered operation.
