# EC1421 - 19EC421 - Analysis-and-Design-of-Analog-ICs
# Design of Integrator using Op-amp.

## AIM:
To design and test the performance of integrator circuits using  Op-amp.

## APPARATUS REQUIRED:

<img width="811" height="206" alt="image" src="https://github.com/user-attachments/assets/fd527bf4-b7bf-4330-9b09-ce7ad607bdeb" />


## THEORY:

INTEGRATOR 
 
A circuit in which the output voltage waveform is the integral of the input voltage 
waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier 
configuration if the feedback resistor Rf is  replaced by a capacitor Cf .  The expression for the 
output voltage is given as, 

Vo = - (1/Rf C1 ) ∫ Vi dt 
 
Here the negative sign indicates that the output voltage is 180 0 out of phase with the 
input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of 
fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger 
than or equal to Rf Cf .

That is, T ≥ Rf Cf 
 
The integrator is most commonly used in analog computers and ADC and signal-wave 
shaping circuits.


## DESIGN
~~~
To obtain the output of an Integrator circuit with component values R1Cf = 0.1ms , Rf = 10 
R1 and Cf = 0.01 µF and also if 1 V peak square wave at 1000Hz is applied as input. 
We know the frequency at which the gain is 0 dB, fb = 1 / (2π R1 Cf) Therefore fb =    
Since fb = 10 fa , and also the gain limiting frequency fa = 1 / (2π Rf Cf) 
We get , R1 =  and hence Rf =

~~~
## CIRCUIT DIAGRAM:
![WhatsApp Image 2025-11-27 at 20 04 22_494ce03d](https://github.com/user-attachments/assets/3f2272fc-aaf2-47de-a83a-58ab42d2c1fe)


## MODEL GRAPH

![WhatsApp Image 2025-11-27 at 20 04 25_52651d8e](https://github.com/user-attachments/assets/b131d2f2-ed12-4b47-80e4-7d861ae68408)


## PROCEDURE:

1. Connections are given as per the circuit diagram 
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC. 
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate 
input voltage is applied to the inverting input terminal of the Op- Amp. 
4. The output voltage is obtained in the CRO and the input and output voltage waveforms 
are plotted in a graph sheet.

## TABULATION:

![WhatsApp Image 2025-11-27 at 20 04 26_44a54bc1](https://github.com/user-attachments/assets/4abc0b9d-bfa5-48f3-b602-61778b50720b)


## GRAPH:

![WhatsApp Image 2025-11-27 at 20 04 27_9e83fd68](https://github.com/user-attachments/assets/0eecbfca-8c62-4be5-863d-0ca395fcdf20)
![WhatsApp Image 2025-11-27 at 20 04 28_124ee455](https://github.com/user-attachments/assets/8ad88612-4529-4957-adda-e4f0718af7e9)


## RESULT:

Thus an Integrator using op-amp are designed and their performance was successfully tested using op-amp IC 741. 
