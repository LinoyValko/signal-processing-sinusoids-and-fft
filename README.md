# Digital Signal Processing 

## Objectives

This project was submitted as part of a homework assignment in the Digital Signal Processing (DSP) course. It explores key concepts in time and frequency domain analysis using Python and includes audio signal processing on a real WAV file.

## Content Overview

The notebook covers:

### Part 1: Synthetic Signal Analysis
- Generation of sine and cosine waves with varying frequency, phase, and amplitude
- Summation of multiple harmonics
- Creation of a pulse train with a specific period and width
- FFT-based frequency analysis and use of `fftshift()`
- Effects of aliasing and time resolution

### Part 2: Real Signal – WAV File Analysis
- Loading and analyzing `harpsi-cs.wav` using `scipy.io.wavfile`
- Time-domain and frequency-domain visualization of the audio signal
- Observing harmonics and spectral content in a real-world waveform

## Files

- `digital_signal_processing_exercise.ipynb`: Colab Notebook containing all analysis and plots.
- `harpsi-cs.wav` – Audio file used for analysis in the frequency domain

## Libraries Used

- numpy
- matplotlib
- scipy.io.wavfile
Install dependencies via:

```bash
pip install numpy matplotlib scipy
