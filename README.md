# Digital Signal Processing 

This project includes exercises and signal analysis tasks performed as part of the homework assignment in the Digital Signal Processing (DSP) course.

## Objectives

- Understand and visualize the behavior of sinusoidal signals.
- Analyze frequency components using the Fourier Transform (FFT).
- Apply filtering techniques in both time and frequency domains.
- Practice signal windowing and zero-padding.

## Content Overview

The notebook covers:

### 1. Signal Creation and Visualization
- Generation of periodic signals: `sin(2πft)`, `cos(2πft)`.
- Exploration of time resolution (`dt`) and its impact on signal representation.

### 2. Frequency Analysis (FFT)
- Application of Fast Fourier Transform to:
  - Pure sinusoidal signals.
  - Sum of signals with different frequencies.
- Observation of spectral leakage and the effect of signal length.

### 3. Filtering and Windowing
- Design of band-pass filters.
- Application of Hamming and rectangular windows.
- Comparison between filtered and unfiltered spectra.

### 4. Zero-Padding
- Exploration of zero-padding effects on frequency resolution.
- Demonstration of FFT interpolation.

## Files

- `digital_signal_processing_exercise.ipynb`: Colab Notebook containing all analysis and plots.

## Requirements

- Python 3.7+
- NumPy
- Matplotlib
- SciPy (optional, if used)

Install dependencies via:

```bash
pip install numpy matplotlib scipy
