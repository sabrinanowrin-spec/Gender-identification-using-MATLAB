# Gender-identification-using-MATLAB
# -Gender-Identification-using-MATLAB
This repository analyzes an audio file containing a human voice and estimates if the person is male or female based on frequency components.

# Gender Identification from Voice (MATLAB)

This project takes an audio file as input, analyzes its time-domain and frequency-domain signals, and records the highest and lowest frequency magnitudes.  
By testing multiple audio files, general frequency ranges for male and female voices can be established.

---

## Features
- **Audio Input**
  - Reads audio files like `.m4a`
  - Plays back the audio for verification

- **Signal Analysis**
  - Plots time-domain waveform
  - Plots frequency-domain spectrum (using FFT)
  - Extracts maximum and minimum frequency components

- **Experimental Dataset**
  - Can be used to build a dataset of male vs. female voice frequency ranges

---

## Files
- `GenderIdentification.m` → MATLAB script for processing the audio
- `audio_file.m4a` → Replace with your desired audio sample

---

## How to Run
1. Open MATLAB.
2. Update the script with the path of your audio file:

```matlab
[audio_file, fs] = audioread('path_to_your_audio_file.m4a');
