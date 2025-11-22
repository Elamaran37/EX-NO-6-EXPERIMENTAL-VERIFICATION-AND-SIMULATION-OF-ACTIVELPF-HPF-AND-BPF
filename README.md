# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:A.27/09/2025,B.04/10/2025,C.11/10/2025**  
**SLOT:5M1-1**
         
---
## AIM:

To obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii) Band pass filter

---

## ** 6 A : LOW PASS FILTER**



## THEORY
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 16K,10K,5.86K | 1 |
| 7 | Capacitor | 0.01uF | 3 |
| 8 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-21 at 18 49 30](https://github.com/user-attachments/assets/37dd640d-76a5-4ef0-8de5-a362d7c71c3c)

### SIMULATION CIRCUIT DIAGRAM:
<img width="1915" height="1079" alt="Screenshot 2025-11-13 181017" src="https://github.com/user-attachments/assets/9889ced3-ecda-4995-affe-0e7690553d93" />



## MODEL GRAPH
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/c8d28c41-6f3e-44a6-a9da-2b798cf07346" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.01 µF, R = 16 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/5bd6f2d8-c1ee-4450-9d89-b47ca89e4feb" />
	
---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/063c9b63-8c7a-4914-8ada-cd146f23fa45" />
### SIMULATION OUTPUT
<img width="1915" height="1078" alt="Screenshot 2025-11-13 181004" src="https://github.com/user-attachments/assets/5cdfe186-5fc6-4d7e-9f0d-2db70cafc52f" />

---

 ## **6B HIGH PASS FILTER**

---

## THEORY
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 16K,10K,5.86K | 1 |
| 7 | Capacitor | 0.01uF | 1 |
| 8 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/948b2f9d-1286-47c9-9523-f757320e1f11" />

### SIMULATION CIRCUIT DIAGRAM:
<img width="1917" height="1079" alt="Screenshot 2025-11-21 201952" src="https://github.com/user-attachments/assets/563abff0-a1ac-44ea-a583-e1d8e1de6779" />



## MODEL GRAPH

<img width="1005" height="382" alt="image" src="https://github.com/user-attachments/assets/22925efc-4abc-4fad-90d5-94f3348c3c0b" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.01 µF, R = 16 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/53bfbe50-d2b3-4773-90c2-3bd99460daf5" />

---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/d968fb1f-90bd-4df3-9291-e1e71f411d9d" />
### SIMULATION OUTPUT:
<img width="1915" height="1076" alt="Screenshot 2025-11-21 202215" src="https://github.com/user-attachments/assets/1d18d5fc-7bd1-41c3-be67-df072b360b6b" />


---

 ## **6C Band Pass Filter**

---

## THEORY
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K | 1 |
| 7 | Capaciotr | 0.1uF | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-22 at 10 48 43](https://github.com/user-attachments/assets/597aee28-ddc7-40d0-927f-fb9695599a08)

### SIMULATION CIRCUIT DIAGRAM:
<img width="795" height="415" alt="Screenshot 2025-11-13 214100" src="https://github.com/user-attachments/assets/a6932d2c-f440-4658-a738-cf2553becafc" />

## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/fbbe2bc9-b00d-489c-95fa-3c83adec4711" />

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-21 at 18 49 20](https://github.com/user-attachments/assets/de8ecaed-0498-4892-9ec4-2df302fd55e7)
### SIMULATION OUTPUT
<img width="784" height="339" alt="Screenshot 2025-11-13 214215" src="https://github.com/user-attachments/assets/659079bd-2bd0-4c13-bf85-3e52f99dce15" />


---
##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
