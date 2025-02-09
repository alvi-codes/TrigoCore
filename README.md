# **TrigoCore: FPGA-Based Trigonometric Function Accelerator**

This repository contains the **three project reports** for *TrigoCore*, a custom digital system designed to accelerate a complex mathematical function involving cosine evaluation using an FPGA. This project was developed as part of Imperial College London's Digital Systems Design module, focusing on optimizing performance, hardware resource utilization, and accuracy.

## **Project Overview**
- **Objective**: Accelerate the computation of a trigonometric function using a DE1-SoC FPGA, transitioning from software-based evaluation to a hardware-optimized solution.
- **Key Achievements**:
  - Achieved a **98.8% reduction in execution time** (from 24,024 ms to 285 ms) for the largest test case by implementing a hardware-based CORDIC algorithm.
  - Optimized the CORDIC algorithm to achieve a mean error within [−0.5×10^(−6), +0.5×10^(−6)] with a 95% confidence level.
  - Finished with an FPGA resource utilization of **4.82%** while maintaining high performance and precision.
  - Implemented a **dual-staged folded CORDIC architecture** with a latency of **14 cycles** per function evaluation, ensuring a low cycle count.
  - Enhanced system performance further by integrating a **hardware accumulator** and through **O3 compiler optimization**.

## **Reports Included**
1. **Report 1** (*Task 1 & 2*): Initial design and implementation of the digital system, including resource utilization, timing analysis, and system performance evaluation.
2. **Report 2** (*Task 3-6*): Optimization of the system by introducing off-chip memory, custom floating-point units, and cosine evaluation strategies (e.g., Taylor series, lookup tables).
3. **Report 3** (*Task 7 & 8 - Latency Minimization*): Final implementation of the hardware-accelerated CORDIC algorithm, including latency minimization, hardware accumulation, and performance improvements.

   **Primary focus** is on **Report 3**, where the **CORDIC algorithm** is implemented and optimized.

## **Technical Skills Demonstrated**
- **FPGA Design**: Utilized Intel Quartus Prime for RTL design, simulation, and synthesis.
- **Hardware Optimization**: Implemented custom instructions, pipelining, and resource-efficient architectures.
- **Mathematical Modeling**: Validated accuracy and performance using Monte Carlo simulations and error analysis.
- **System Integration**: Integrated hardware and software components to achieve significant performance gains.

## **Coursework Requirements**
The **Coursework_Requirements** document outlines the **project scope, aims, and targets**. Please review this document to understand the **core objectives** and **development steps** undertaken in this project.

---

### **How to Use This Repository**
- The repository contains the three project reports in PDF format.
- No code is included due to copyright concerns, but the reports provide detailed insights into the design, implementation, and optimization process.

---
