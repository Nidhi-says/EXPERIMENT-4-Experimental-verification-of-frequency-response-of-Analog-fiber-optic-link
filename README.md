
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog link.

---


## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="1280" height="715" alt="image" src="https://github.com/user-attachments/assets/c7d59c66-48e8-4b75-bfc7-68a6cac89805" />


---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="1280" height="437" alt="image" src="https://github.com/user-attachments/assets/e6ebae09-edc6-4b9c-a933-42a0985180e2" />

---

## TABULATION  
**Transmission through Analog Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|50              |138                           |0.644         |1.938       |
|3.33            |150                           |0.700         |1.549       |
|9.86            |148                           |0.691         |1.605       |
|10.2k           |148                           |0.691         |1.605       |
|13k             |146                           |0.68          |1.674       |
|16k             |144                           |0.672         |1.726       |
|33M             |140                           |0.654         |1.844       |
|3M              |136                           |0.028         |1.526       |

---

## MODEL GRAPH

<img width="987" height="1280" alt="image" src="https://github.com/user-attachments/assets/b2f54943-2296-4422-86a0-95a938dee8eb" />

---

## OUTPUT GRAPH

<img width="1280" height="1014" alt="image" src="https://github.com/user-attachments/assets/c0ae32a4-05c5-451a-b653-e47d830aceab" />

---
## RESULT

Thus the relationship between input and received signal of a 660nm fiber optic cable using analog link is successfully analyzed.
