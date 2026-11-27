
This project focuses on the design and comparative analysis of a two-stage CMOS operational amplifier (Op-Amp) using 180nm and 90nm CMOS technologies.

## Design and Comparative Analysis of Two-Stage CMOS Operational Amplifier Under Technology Scaling (180nm to 90nm)

 ## 1. Project Overview

This project focuses on the design and comparative analysis of a two-stage CMOS operational amplifier (Op-Amp) using 180nm and 90nm CMOS technologies.

The proposed design uses a Miller-compensated two-stage architecture to achieve high voltage gain and stable operation. The first stage provides differential amplification, while the second stage provides additional voltage gain and drives the output load.

The design is implemented and simulated using Cadence Virtuoso. The performance of the operational amplifier is evaluated under different technology nodes to understand the impact of technology scaling on important analog performance parameters.

## 2. Objectives

- Design a two-stage CMOS operational amplifier.
- Implement Miller compensation for frequency stability.
- Compare performance under 180nm and 90nm CMOS technologies.
- Analyze DC gain, gain-bandwidth product (GBW), and phase margin.
- Study the effect of technology scaling on analog circuit performance.
  
## 3. Circuit Architecture

The two-stage CMOS Op-Amp consists of:
<img width="694" height="162" alt="image" src="https://github.com/user-attachments/assets/244da746-c02e-48d7-a0b3-9803fb253afe" />

<img width="496" height="361" alt="image" src="https://github.com/user-attachments/assets/f6702804-131d-4112-89db-0774b309e555" />

- First Stage: Differential amplifier with an active load for differential-to-single-ended conversion.
- Second Stage: Common-source gain stage for additional voltage amplification.
- Miller Compensation: Compensation capacitor connected between the first-stage and output nodes to improve frequency stability.
- Biasing Circuit: Provides the required operating currents for the amplifier.

## 4. Design Specifications
<img width="366" height="323" alt="image" src="https://github.com/user-attachments/assets/71c81efb-44aa-45d1-abd8-cb135e30ca59" />

 ## 5. circuit diagram and testbench:
    Simulation circuit of 180 nm:

     <img width="1600" height="754" alt="image" src="https://github.com/user-attachments/assets/7747d609-f7bc-4a71-8828-0108b46e48a9" />

     Simulation circuit of 90 nm:

    <img width="1600" height="784" alt="image" src="https://github.com/user-attachments/assets/e3066370-bd11-462c-bc0d-0aa4223423c8" />


     Slew Rate testbench ckt:

     a) 180 nm


     <img width="1600" height="791" alt="image" src="https://github.com/user-attachments/assets/697b526f-f836-4887-b04e-5e160171a07a" />

       a) 90 nm

     <img width="1600" height="784" alt="image" src="https://github.com/user-attachments/assets/82ae6d6c-4e3a-4acc-bbb3-732fad9a31da" />

## 6. Simulation Results:

  i) Gain, Phase margin and GBW at Vcm=1.6V for 180nm technology:

   <img width="1600" height="671" alt="image" src="https://github.com/user-attachments/assets/4fe28fe4-68e1-4d01-997c-db1f0edac701" />

 ii) Gain, Phase margin and GBW at Vcm=0.8V for 180nm technology:
  
   <img width="1600" height="671" alt="image" src="https://github.com/user-attachments/assets/69d7c6b0-5b43-43f2-a7ee-ae32fff632a5" />

 ii) Gain, Phase margin and GBW at Vcm=1.6V for 90nm technology:

   <img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/b80ed955-cb6d-4fc4-a2ef-d69419197d7b" />

  
iv) Gain, Phase margin and GBW at Vcm=0.8V for 90nm technology:

   <img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/95fc20a3-71ca-4791-9356-6559a1f96190" />



The following are the slew rate simulation results:

In 180 nm tech:

<img width="1600" height="671" alt="image" src="https://github.com/user-attachments/assets/5b57d8b3-c039-4a53-a536-50b1ae4e5ae1" />

In 90 nm tech:

<img width="1600" height="712" alt="image" src="https://github.com/user-attachments/assets/27cec7d8-e6fa-48c8-83e4-47aeada9425f" />



<img width="560" height="284" alt="image" src="https://github.com/user-attachments/assets/741fecaa-f490-425b-b347-39bbd30107f4" />


## 7. Tools and Technologies

- Cadence Virtuoso
- CMOS Analog Circuit Design
- 180nm and 90nm CMOS technology
- AC Analysis
- DC Operating Point Analysis
- Transient Analysis

## 8. Key Features

- Two-stage CMOS amplifier architecture.
- Miller frequency compensation.
- Comparative analysis across technology nodes.
- Evaluation of gain and frequency response.
- Analog performance optimization.

## for more detail read journal paper on this project:
https://jseepublisher.com/volume-36-issue-4-2026/
