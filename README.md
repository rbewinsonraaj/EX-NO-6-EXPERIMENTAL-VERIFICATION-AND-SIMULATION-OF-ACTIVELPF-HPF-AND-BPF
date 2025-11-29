# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP

---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-29 at 11 06 21_c529b464](https://github.com/user-attachments/assets/201dcce8-c53e-492d-8415-52b90a143b52)

## MODEL GRAPH
![WhatsApp Image 2025-11-29 at 11 06 38_bf68249c](https://github.com/user-attachments/assets/fbcbee83-41e5-42a4-a671-66498bbd69ba)

---

## DESIGN

<img width="429" height="172" alt="image" src="https://github.com/user-attachments/assets/bfa3de8d-f4aa-4209-9e71-0f6f4f7c3aee" />


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-29 at 11 12 41_a13d42c4](https://github.com/user-attachments/assets/a2bf3822-5d43-4620-a37e-b295cbed5c51)

		

---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1189" height="806" alt="image" src="https://github.com/user-attachments/assets/00852b24-7683-4b27-94be-68e894846215" />

---

 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-29 at 11 07 19_df66c0b8](https://github.com/user-attachments/assets/7355c23e-d073-498f-a984-b6802939295f)


## MODEL GRAPH

![WhatsApp Image 2025-11-29 at 11 07 45_a87b3942](https://github.com/user-attachments/assets/392c6b4c-2e14-402c-95e3-74181e71f025)

---

## DESIGN

<img width="441" height="230" alt="image" src="https://github.com/user-attachments/assets/28d7f103-2335-47e4-869c-f7339cecab03" />



## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
![WhatsApp Image 2025-11-29 at 11 12 41_bb028ffe](https://github.com/user-attachments/assets/000171b5-df42-4ae7-be8c-22ddaa7679ce)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 11 03 32_9e9cf8a3](https://github.com/user-attachments/assets/e7b5852c-919b-4792-9d9d-19ee694c3c8e)

---

 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-29 at 11 09 07_c05d3638](https://github.com/user-attachments/assets/af89110f-08d7-4f84-be7c-80be4dc5029d)

## MODEL GRAPH

![WhatsApp Image 2025-11-29 at 11 09 17_a8440444](https://github.com/user-attachments/assets/4e1b73ec-9476-4f67-88d1-b72a112c1cb8)


---

## DESIGN

<img width="469" height="203" alt="image" src="https://github.com/user-attachments/assets/2b10e864-26f2-4857-95f0-4dfb67c2a594" />



## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
![WhatsApp Image 2025-11-29 at 11 12 42_ab7485e7](https://github.com/user-attachments/assets/187faf9d-2092-48d4-808f-81f709d63a97)


---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 11 08 41_16ead1b0](https://github.com/user-attachments/assets/ef496f89-1342-42bb-b431-41ede9d45e2c)

---
##RESULT:
---
![WhatsApp Image 2025-11-29 at 11 20 28_a0fbd808](https://github.com/user-attachments/assets/433e7fbe-26ab-4a5d-bbd6-418d9edfaeac)


   
