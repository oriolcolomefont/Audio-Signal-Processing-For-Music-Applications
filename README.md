# Audio Signal Processing For Music Applications
Assignments for Audio Signal Processing for Music Applications on MTG-UPF Msc Sound And Music Computing. 

Important note: It's for my personal learning purpose only.


## Week 1 - Python and sounds
This exercise aims to get familiar with some basic audio operations using Python. There are four parts to it: 1) Reading an audio file, 2) Basic operations with audio, 3) Python array indexing, and 4) Downsampling audio - Changing the sampling rate.

## Week 2 - Sinusoids and the DFT
Doing this exercise you will get a better understanding of the basic elements and operations that take place in the Discrete Fourier Transform (DFT). There are five parts: 1) Generate a sinusoid, 2) Generate a complex sinusoid, 3) Implement the DFT, 4) Implement the IDFT, and 5) Compute the magnitude spectrum of an input sequence.

## Week 3 - Fourier properties
With this exercise you will get a better understanding of some of the Fourier theorems and of some useful properties of the DFT. You will write code to implement and verify several properties of the DFT that are discussed in the lectures. You will also learn to use the dftModel.py module of sms-tools, which contains the basic python functions implementing the DFT. There are five parts in the exercise: 1) Minimize energy spread in DFT of sinusoids, 2) Symmetry properties of the DFT, 3) Suppressing frequency components using DFT model, and 4) FFT size and zero-padding.

## Week 4 - Short-time Fourier Transform
Doing this exercise you will learn about the concept of the main lobe width of the spectrum of a window and you will better understand the short-time Fourier transform (STFT). You will also use the STFT to extract basic rhythm related information from an audio signal, implementing an onset detection function, which is one of the rhythm descriptors often used in music information retrieval to detect onsets of acoustic events.

There are four parts in this exercise. 1) Extracting the main lobe of the spectrum of a window, 2) Measuring noise in the reconstructed signal using the STFT model, 3) Computing band-wise energy envelopes of a signal, 4) Computing an onset detection function.

## Week 5 - Sinusoidal model
In this exercise you will experiment with the sinusoidal model, measuring and tracking sinusoids in different kinds of audio signals. You will use the sinusoidal model to analyze short synthetic sounds with the goal to better understand various aspects of sinusoid estimation and tracking. You will experiment with different parameters and enhancements of the sinusoidal modeling approach.

There are five parts in this exercise: 1) Minimizing the frequency estimation error of a sinusoid, 2) Tracking a two component chirp, 3) Tracking sinusoids of different amplitudes, 4) Tracking sinusoids using the phase spectrum, and 5) Sinusoidal modeling of a multicomponent signal.

## Week 6 - Harmonic model
This exercise on the Harmonic model will help you better understand the issue of fundamental frequency (
) estimation by analyzing several sound examples with harmonic content. There are four parts to this exercise: 1) Estimate fundamental frequency, 
, in an polyphonic audio file, 2) Segmentation of stable note regions in an audio signal using 
, 3) Compute amount of inharmonicity present in a sound, and 4) Improving the implementation of the two way mismatch 
 estimation algorithm.


## Week 7 - Sinusoidal plus residual model
In this exercise you will analyze and synthesize sounds using the Harmonic plus Stochastic (HPS) model, hpsModel.py. There are two questions in this exercise. In the first one you will analyze a speech sound that we give and in the second one you will analyze a sound of your choice, in both cases using the HPS model. For each question, you will first describe some of the sound characteristics by listening to the sounds and visualizing their spectrogram, characteristics that should be of relevance for the analysis/synthesis with the HPS model. Then from the described characteristics you will set the appropriate values for the different analysis parameters, explaining the choices you make, and analyze and synthesize the sounds with the HPS model software.

For this exercise, you can use models_GUI.py, to experiment with the parameters easily and then use them in here. Feel free to modify the code of the model if needed and add it also here.
