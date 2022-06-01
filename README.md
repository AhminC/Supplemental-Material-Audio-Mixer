# Supplemental Material Audio Mixer

# Intro
Audio mixer, also called mixing console, is an electronic device for combining (also called “mixing”) and modifying audio signals. 
Audio mixers can be analog or digital type. Digital audio mixer use digital signal processing and analog mixers are usually 
based on operational amplifiers (opamps) electronic circuits. In this project we will build a three-channel analog audio mixer with opamps, resistance and 
capacitance. The input audio signals can be anything from 
microphones, cell phones and computers. The mixer will be 
able to combine audio signals from different signal sources, 
change the volumes of each input channel, as well as the 
overall volume of the mixer output. Then, we are going to add more circuits for audio equalizer, which 
boost or attenuate a range of frequencies, e.g. bass, midrange, and treble, and perform general 
equalization control at the output. 

# Circuit Diagram I
The system is shown, which contains three input signals, preamplifier, summing amplifier, 
equalizer and a speaker.  

* The three signal sources, which are three channels, provide signals to the system. The source can 
be from any electronic devices, such as cell phones and computers. The microphone is used to 
convert acoustic signal to electric signals. 
* The preamplifier is only implemented to the microphone source because other audio signals, like 
those from cell phones or computers, have already been pre-amplified before come into the 
circuit, while the signal from microphone are not amplified yet.  
* The summing amplifier is utilized to combine the three channels and control volumes of each 
channel. For example, if source 1 is expected to be boosted and source 2 is to be attenuated, the 
summing amplifier is the circuit to perform this function. 
* The equalizer is the core to boost or attenuate signals in a range of frequencies. 
* The speaker is the device to covert electric analog signal to acoustic signals. 

![](systemBlock.png)

Diagram of equalizer
![](equalizer.png)

# Circuit Diagram II
Preamplifier
The preamplifier circuit is shown. The potentiometer is used to change the gain of the circuit 
and the capacitor is added to remove the white noise at high frequency range. 
![](preamplifier.png)

Summing Amplifier 
The summing amplifier is to mix signals of three channels, while the three potentiometers are used to 
change volumes. The are to change volume of each channel while the are used to 
change the whole volume. 
![](summingAmplifier.png)

# Circuit
![](circuit.jpg)
