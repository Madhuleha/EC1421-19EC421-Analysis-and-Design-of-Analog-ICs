# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
![WhatsApp Image 2025-11-27 at 20 29 44_5c6629fc](https://github.com/user-attachments/assets/2bd95e64-e4a4-4aaf-9fac-6c51a565ec73)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 20 29 45_cbd355a7](https://github.com/user-attachments/assets/88b871a3-ede8-4f1f-9337-289b38072a5f)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 20 29 45_cf8a6c7e](https://github.com/user-attachments/assets/976d0bc4-b1d1-45cd-b10b-6adba330eebb)

## MODEL GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 20 29 45_0af87e00](https://github.com/user-attachments/assets/37718116-4619-449c-a343-75a3cd1a0f07)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 20 29 45_185bff3a](https://github.com/user-attachments/assets/d56ceca7-04d6-427e-ac5b-a8f0fdf98eec)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 20 29 46_6331c04b](https://github.com/user-attachments/assets/0f898b3d-62ee-4b8c-8040-1df221257cf4)

## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 20 29 47_217b46d6](https://github.com/user-attachments/assets/9a8a0567-217d-43cd-8855-f20e1e941d89)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 20 29 47_84fce57d](https://github.com/user-attachments/assets/23a39a0f-4e19-403b-95c6-6fdd4e4d6eab)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 20 29 46_a1c37530](https://github.com/user-attachments/assets/eac8e608-004e-40f4-a9e5-ca96c86e79b6)

## CALCULATIONS:
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## GRAPH:
## LOW_PASS
<img width="1534" height="1069" alt="image" src="https://github.com/user-attachments/assets/006ec8bd-e314-4804-8c41-e5609034243d" />


## HIGH-PASS
<img width="1519" height="1041" alt="image" src="https://github.com/user-attachments/assets/aa74aaa4-9588-47f1-80ee-c4dd84d2d145" />

## BAND-PASS
<img width="1427" height="1042" alt="image" src="https://github.com/user-attachments/assets/19fd7fc1-0341-4a46-be6e-3cf6c5276eeb" />

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

