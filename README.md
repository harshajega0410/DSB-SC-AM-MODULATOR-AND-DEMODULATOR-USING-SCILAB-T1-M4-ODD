# DSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
# DSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** A sinusoidal signal that will be modulated.
* **Carrier Signal:** A high-frequency sinusoidal signal used for modulation.

### 3. DSBSC Modulation:

* **Modulated Signal:** Multiply the message signal by the carrier signal to produce the DSBSC signal.

### 4. DSBSC Demodulation:

* **Multiplication:** Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).
* **Low-pass Filtering:** Apply a Butterworth low-pass filter to remove the high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION


<img width="888" height="1522" alt="image" src="https://github.com/user-attachments/assets/5c6a0407-2a66-465b-890b-f0c49c547704" />


---
## CALCULATION
<img width="1600" height="1582" alt="image" src="https://github.com/user-attachments/assets/6a695d40-eb3e-4102-8688-8c87d7e08a4e" />



## MODEL GRAPH
<img width="1071" height="634" alt="image" src="https://github.com/user-attachments/assets/6028b5f2-6666-47ce-a7ae-88a3477fd957" />


# RESULT
Successfully performed SSBSC modulation and demodulation using SCI LAB.
