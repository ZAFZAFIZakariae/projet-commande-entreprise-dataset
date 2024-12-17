Spectrogram Dataset Generation:

This repository provides code to generate spectrograms from IQ (In-Phase and Quadrature) audio signals stored in .wav files. The script processes input signals by segmenting them, computing spectrograms using the Short-Time Fourier Transform (STFT), and saving them in a CSV format. It also includes a frequency-shifting operation to augment the dataset with shifted spectrograms. The key features include customizable FFT size (NFFT), overlap (noverlap), and frequency shift values. The generated spectrogram data can be used for machine learning tasks, signal processing, or audio analysis.

Input: .wav files containing IQ signal pairs.
Output: A CSV file with flattened spectrogram matrices.
