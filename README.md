# Introduction to OptiPerformer

## Aim
To download and install OptiPerformer software on the computer and run a sample file.

---

## Software Required

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the capabilities of OptiSystem and creates dynamic design scenarios for students.

The system is instrumented with:
- An optical power meter at the input to the receiver (or the output of the fiber)
- A bit error rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from the official website:  
   https://optiwave.com

2. Copy the `Introduction_OptiPerformer.osp` file to the PC.

3. Start the OptiPerformer software.

4. Open the fiber optic system file using either:
   - The **File** menu, or  
   - The **Open File** button

5. Study the system layout, which consists of the following sections:

   **Transmitter Section**
   - Binary source (PRBS generator)
   - Electrical pulse generator
   - Laser diode
   - External modulator

   **Receiver Section**
   - Photodiode
   - Low-pass filter
   - Decision circuit with BER analyzer

   *(These components will be explained in detail later in the course.)*

6. Run the simulation by clicking the **Start** button.
   - Simulation progress will be displayed.
   - The message **"Calculation Finished!"** appears after completion.

7. Double-click the **Optical Power Meter** and **BER Analyzer**.
   - Move the windows for better visibility.
   - In the BER analyzer window, enable **Show Eye Diagram**.
   - The optical power meter displays received power in watts and dBm.
   - The BER analyzer displays the eye diagram, maximum Q factor, and minimum BER.

8. The simulation runs for **5 iterations**, with fiber length varying from **50 km to 150 km**.
   - The iteration index is displayed in the upper-right corner of the layout.
   - Use the forward and reverse buttons to switch between iterations.
   - Observe the changes in received power, eye diagram, Q factor, and BER.

---

## Tabulation

<img width="1600" height="1310" alt="image" src="https://github.com/user-attachments/assets/eab627e9-49b0-4ccf-8339-53e7790f0961" />



---


---

## Graph

<img width="1919" height="1072" alt="Screenshot 2026-01-29 213008" src="https://github.com/user-attachments/assets/78d340f5-e0c9-4ee5-b782-115b9f0c0f2c" />


---


## Description

As the fiber length increases, signal attenuation and dispersion cause the transmitted pulses to spread and distort. This spreading results in overlapping of adjacent symbols, reducing the eye opening in the eye diagram.

A reduced eye opening indicates increased intersymbol interference, which raises the probability of bit errors. Consequently, the Q factor decreases and the BER increases, degrading the overall performance and reliability of the optical communication system.

---

## Result

Thus, the OptiPerformer software was successfully installed, and the given sample file was executed successfully.
