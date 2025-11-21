# SIMULATION-OF-AUTOCORRELATION-AND-PSD-USING-SCILAB-1

__AIM:__

Write a program for Autocorrelation and PSD of signals in SCILAB and verify Wiener-Khinchin relation. 


__EQUIPMENTS Needed:__

.Computer with i3 Processor 

.SCI LAB


__THEORY:__

The Wiener-Khinchin theorem states that the power spectral density of a wide sense stationary random process is the 
Fourier transform of the corresponding autocorrelation function.

__Algorithm:__

 1.Load or Define the Signal: Input your time-domain signal. 

 2.Compute Autocorrelation: Calculate the autocorrelation function of the signal.

3.Compute Power Spectral Density (PSD): Estimate the PSD of the signal, either directly using a method like
Welch’s periodogram or by using the Fourier transform of the autocorrelation.

4.Plot Results: Visualize the autocorrelation function and PSD. 

__PROCEDURE:__


Refer Algorithms and write code for the experiment. 

Open SCILAB in System 

Type your code in New Editor 

Save the file 

Execute the code 

If any Error, correct it in code and execute again 

Verify the generated waveform using Tabulation and Model Waveform 

__PROGRAM:__
```
x = input("Enter the sequence x = ");   // example: [1 2 3]
Rxx = corr(x, x);
clf();
plot(Rxx);
xtitle("Autocorrelation of x","Lag","Rxx");
```
__OUTPUT:__

<img width="1280" height="723" alt="517247825-f3cf0fee-827b-4c6d-ba2d-35d85c4388c6" src="https://github.com/user-attachments/assets/f9b0652c-da34-46ac-a3a5-e66cdda3c2f0" />

__RESULT:__

Thus the Autocorrelation and PSD of signals in SCILAB and verify Wiener-Khinchin relation was verified succesfully and it output was verified.

