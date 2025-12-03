# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR

## AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
## THEORY:
RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
	The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR

![WhatsApp Image 2025-12-02 at 18 50 02_9d5e853c](https://github.com/user-attachments/assets/c8ce6ba5-c1d5-47ae-a502-959db6e2d787)


---

## MODEL GRAPH
<img width="414" height="324" alt="image" src="https://github.com/user-attachments/assets/3389b740-b70e-4148-9bf9-e5319627260f" />

## DESIGN

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

<img width="1344" height="1527" alt="image" src="https://github.com/user-attachments/assets/29d03f67-4f2c-4f8d-a2b6-22d715dd80f0" />


---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-12-02 at 18 50 45_ca7ab810](https://github.com/user-attachments/assets/b5cfb60c-6235-44df-a383-8dd9846f4f6e)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-02 at 18 51 35_e5ea2125](https://github.com/user-attachments/assets/1df79f0a-52bd-4051-a274-43aa9a465bcf)

---
## THEORY
 WIEN BRIDGE

# DATE: 1.11.2025
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR

![WhatsApp Image 2025-12-02 at 19 00 29_09dfe112](https://github.com/user-attachments/assets/efcd6852-8753-4c87-9d9f-2682c62ecd2b)


---
## MODEL GRAPH
<img width="414" height="325" alt="image" src="https://github.com/user-attachments/assets/1cc285f7-05c7-4b65-af59-b28cf039fcd3" />

---

## DESIGN

## WIEN BRIDGE OSCILLATOR

Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ

<img width="1439" height="1155" alt="image" src="https://github.com/user-attachments/assets/a02ca4b5-2ea0-4e6d-8989-8434bcd6a584" />

---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-12-02 at 19 00 43_726d227c](https://github.com/user-attachments/assets/3524a14c-1133-4b18-ac9c-796de45e6160)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-02 at 19 01 00_f6a0b4bf](https://github.com/user-attachments/assets/391953e2-ce92-4f23-a054-01a655798f65)



---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
