## :sparkles:**Function**
**Analysis and Control of Mechatronic Multi-Variable Systems**
This repository contains the modeling and controller design for complex mechatronic systems. The project is divided into two main areas of focus: the static/dynamic decoupling of multi-input multi-output (MIMO) systems and the discrete-time state-space control of unstable plants.

---

## **Part 1: Decoupling of Multi-Variable (MIMO) Systems**
The first part investigates a system with multiple inputs and outputs (a handling device featuring a linear and a rotational axis). Without correction, the axes interfere with each other, making precise control difficult.

**Implementation:**

* **System Analysis:** Determination of the cross-couplings between the inputs and outputs within the transfer matrix.

* **Decoupling Network:** Calculation and implementation of a decoupling matrix so that each input variable acts exclusively on its corresponding output variable.

---

## **Part 2: State-Space Control and Discrete-Time Implementation**
The second part focuses on stabilizing an unstable system (an inverted pendulum on a cart). For this purpose, a modern state-space control approach was chosen.

**Core Aspects of the Design:**

:white_check_mark:**State Feedback:** Calculation of the feedback matrix for targeted pole placement in order to stabilize the system and meet dynamic performance requirements (settling time, overshoot).

:white_check_mark:**Discrete-Time Control:** Since real-world controllers run on microcontrollers, the controller was discretized taking a fixed sampling time into account.

:white_check_mark:**Controller without Observer:** In this scenario, it is assumed that all state variables (positions and velocities) are directly measurable or can be obtained through simple differentiation, eliminating the need for a Luenberger observer.

---

## :man_technologist: **Autor**
**Ezechiel Tonkeme**



<img width="600" height="340" alt="image" src="https://github.com/user-attachments/assets/b1c95e7e-f03d-4152-bff0-c3b789d6b15b" />
