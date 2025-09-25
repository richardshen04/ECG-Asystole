# ECG-Asystole
This notebook contains a complete, self‑contained pipeline to:

1. Load a 1D ECG signal from CSV (first column)
2. Fast Fourier Transform (FFT)
3. Band‑pass filter (5–50 Hz)
4. Robust R‑peak detection (MAD‑adaptive + width + slope)
5. Sliding‑window asystole detection (4 s window, 1 s hop, ≥3 s without R)
6. Plot overview (raw + alarm) and a spectrogram (0–60 Hz)
7. Export JSON summary and an optional HTML report
8. (Optional) Batch process a folder of CSVs
Tip: Put your file into the pop-up system file selection dialog. Sampling rate defaults to 250 Hz.
