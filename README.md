# TwinCAT 3 - PLC Programming Learning Path

This repository serves as my personal **Industrial Automation Laboratory**. It documents my step-by-step progression from basic digital I/O handling to advanced Motion Control and Machine Safety, developed during my **M.Eng. in Industry 4.0** studies. 

All projects are programmed using **Structured Text (ST)** within the Beckhoff TwinCAT 3 environment.

---

## Curriculum & Project Breakdown

To ensure a solid foundation in industrial automation, I structured my learning path into three distinct phases:

### Phase 1: PLC Fundamentals & Logic
| # | Project Folder | Core Concept | Skills Acquired |
|:-:|:---|:---|:---|
| **01** | `1_LED_Button` | Digital I/O & Basic Logic | PLC execution cycle, POUs, Basic ST syntax. |
| **02** | `2_Blinking_LED` | Timers (TON/TOF) | Cyclic tasks, variable scope tracking, basic debugging. |
| **03** | `3_Motor_Control` | Start/Stop Latching | Logical control, output holding, Watch window usage. |
| **04** | `4_Limit_Switch` | Endstop & Safety Logic | Conditional statements, digital input interruption. |
| **05** | `5_Analog_Control` | Analog Signal Processing | REAL/INT conversions, potentiometer scaling, Scope monitoring. |

### Phase 2: System Integration & Advanced Control
| # | Project Folder | Core Concept | Skills Acquired |
|:-:|:---|:---|:---|
| **06** | `6_Advanced_HMI` | SCADA / Visualization | Linking variables to UI, interactive dashboards, user input. |
| **07** | `7_EtherCAT_Mapping` | Fieldbus Configuration | EtherCAT setup, real-time I/O mapping, task cycle optimization. |
| **08** | `8_Industrial_Startup` | PID Control Loops | Mathematical operations, real-time process tuning. |
| **09** | `9_State_Machine_Press` | Sequential Control | Multi-task management, CASE state machines, complex debugging. |
| **10** | `10_Object_Oriented_PLC` | Object-Oriented Logic & IIoT | Data logging, alarms, TCP/IP concepts, integrated HMI+PLC. |

### Phase 3: Specialized Industrial Modules
| # | Project Folder | Core Concept | Skills Acquired |
|:-:|:---|:---|:---|
| **11** | `11_Motion_Control_Axis` | Virtual Servo Control (NC) | PLCopen blocks (`MC_Power`, `MC_MoveAbsolute`), precise positioning for robotics and CNC. |
| **12** | `12_TwinSAFE_EStop` | Machine Safety (SIL) | Independent safety logic, ESTOP hardware interruption, CE/TÜV standards. |
| **13** | `13_Motion_Absolute` | Dynamic Recipe Management | Using `STRUCT` data types, multi-product line simulation, on-the-fly parameter switching. |

---

## The Capstone Project
This learning path directly led to my comprehensive Capstone Project. If you want to see all these skills combined into a single, fully functional IIoT simulation, please check out my main repository:

---
**Ahmed Haltas** | Mechanical Engineer & Automation Enthusiast 
📫 [LinkedIn Profile](https://www.linkedin.com/in/ahmedhaltas/)
