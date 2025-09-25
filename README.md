# ECG-Asystole
This notebook contains a complete, self‑contained pipeline to:

Load a 1D ECG signal from CSV (first column)
Fast Fourier Transform (FFT)
Band‑pass filter (5–50 Hz)
Robust R‑peak detection (MAD‑adaptive + width + slope)
Sliding‑window asystole detection (4 s window, 1 s hop, ≥3 s without R)
Plot overview (raw + alarm) and a spectrogram (0–60 Hz)
Export JSON summary and an optional HTML report
(Optional) Batch process a folder of CSVs
Tip: Put your file into the pop-up system file selection dialog. Sampling rate defaults to 250 Hz.
