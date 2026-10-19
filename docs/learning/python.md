# Python Basics

**Goal:** Understand variables, conditions, loops, and functions.

## 1. Variables

```python
robot_name = "Sumo Bot"
battery_voltage = 7.4
is_ready = True
print(robot_name, battery_voltage, is_ready)
```

## 2. Conditions

```python
distance_cm = 18
if distance_cm < 20:
    print("Object detected")
else:
    print("No object nearby")
```

## 3. Loops

```python
for step in range(3):
    print("Testing step", step + 1)
```

## 4. Functions

```python
def is_object_near(distance_cm, threshold_cm=20):
    return distance_cm < threshold_cm

assert is_object_near(10) is True
assert is_object_near(30) is False
```

!!! note "Simulation only"
    The code above demonstrates Python concepts; it is not code for controlling the team's actual robot.

## Exercise

Write a function that returns `"STOP"` when distance is below 10 cm and `"MOVE"` otherwise. Test it with 5 cm and 20 cm.

**Checkpoint:** You can explain a function's input and return value.
