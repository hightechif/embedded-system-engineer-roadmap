# 🚀 Embedded Systems Mastery Curriculum

**Target Goal:** Transition from Mobile/Android Engineer to Professional Embedded & Robotics Specialist.
**Target Hardware:** ARM Cortex-M (STM32 Ecosystem).
**Total Estimated Effort:** ~800–1,000 Hours (12 Months at 15–20 hrs/week).

---

## 🛠 Phase 1: The "Manual Transmission" (Months 1–3)
*Focus: Mastering C and Computer Architecture Foundations.*

### **Checklist:**
- [ ] **The C Language (Embedded Style):**
    - [ ] Understand Pointers and Memory-Mapped I/O.
    - [ ] Master the `volatile`, `static`, and `const` keywords.
    - [ ] Practice Bit Manipulation (AND, OR, XOR, NOT, Bit-Masking).
    - [ ] Learn Structs, Unions, and Bit-fields for register access.
- [ ] **Computer Architecture:**
    - [ ] Explain the Fetch-Decode-Execute cycle.
    - [ ] Identify Memory Layout: Flash (Code) vs. SRAM (Data).
    - [ ] Manage the Stack (Local variables) vs. the Heap (Dynamic allocation).
- [ ] **Digital Logic:**
    - [ ] Study Logic Gates, Latches, and Flip-Flops (SR, D-Type).
    - [ ] Achieve fluency in Binary and Hexadecimal.

### **Milestone:**
- [ ] **Project:** Write a C program that performs bitwise manipulation on a virtual 32-bit register to toggle specific "hardware" bits without affecting others.

---

## ⚡ Phase 2: Bare-Metal Mastery (Months 4–6)
*Focus: Hardware-Software Interface & STM32 Microcontrollers.*

### **Checklist:**
- [ ] **STM32 Ecosystem Setup:**
    - [ ] Install STM32CubeIDE or VS Code + ARM GCC.
    - [ ] Learn to navigate a 1,000+ page **Reference Manual**.
- [ ] **Peripheral Drivers (Register-Level):**
    - [ ] **GPIO:** Configure Digital Input/Output and Pull-up/down resistors.
    - [ ] **UART:** Establish serial communication between MCU and PC.
    - [ ] **Timers:** Generate PWM for motors and implement precise delays.
    - [ ] **I2C/SPI:** Interface with external sensors (IMUs, OLEDs).
- [ ] **Advanced Data Handling:**
    - [ ] **Interrupts:** Implement non-blocking hardware event handling.
    - [ ] **DMA (Direct Memory Access):** Offload data movement from the CPU.

### **Milestone:**
- [ ] **Project:** Create a "Flight Data Logger" that reads IMU values via I2C using DMA and sends data to a PC via UART—all written at the register level (no HAL).

---

## ⚙️ Phase 3: The Real-Time Mindset (Months 7–9)
*Focus: RTOS (Real-Time Operating Systems) and Concurrency.*

### **Checklist:**
- [ ] **RTOS Fundamentals (FreeRTOS or Zephyr):**
    - [ ] Understand the Scheduler and Task Priorities.
    - [ ] Master Context Switching and Tick Rates.
- [ ] **Inter-Task Communication:**
    - [ ] **Semaphores & Mutexes:** Solve resource contention/race conditions.
    - [ ] **Queues:** Implement safe data passing between tasks.
- [ ] **Embedded DevOps:**
    - [ ] Learn Build Systems (CMake/Make).
    - [ ] Write custom Linker Scripts.
    - [ ] Implement Unit Testing (Ceedling or Google Test).

### **Milestone:**
- [ ] **Project:** Build a multi-tasking system: Task A (Emergency Stop - High Priority), Task B (PID Control - Med Priority), and Task C (Bluetooth Telemetry - Low Priority).

---

## 🤖 Phase 4: The Niche Specialist (Months 10–12)
*Focus: Robotics, Control Theory, and Professional Standards.*

### **Checklist:**
- [ ] **Robotics Integration:**
    - [ ] Port PID or MPC control algorithms to C.
    - [ ] Understand Fixed-point vs. Floating-point math performance.
- [ ] **Safety & Industry Standards:**
    - [ ] Apply **MISRA C** coding standards.
    - [ ] Study Bootloaders and Secure Boot.
- [ ] **Communication Protocols:**
    - [ ] **CAN Bus:** Implement communication for automotive/industrial use.
    - [ ] **MQTT/IoT:** Connect your robot to a network.

### **Milestone (The Capstone):**
- [ ] **Project:** Build an autonomous mobile robot using SLAM or Motion Planning on STM32 with an RTOS.

---

## 📊 Summary of Required Time

| Phase | Duration | Weekly Commitment | Total Hours |
| :--- | :--- | :--- | :--- |
| **1. Foundation** | 12 Weeks | 15 Hours | 180 hrs |
| **2. Bare-Metal** | 12 Weeks | 20 Hours | 240 hrs |
| **3. RTOS/DevOps** | 12 Weeks | 20 Hours | 240 hrs |
| **4. Specialization** | 12 Weeks | 20 Hours | 240 hrs |
| **GRAND TOTAL** | **48 Weeks** | **~18.75 Hours** | **~900 Hours** |
