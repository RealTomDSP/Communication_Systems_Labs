Lab 1: Fourier Series

Exploration of periodic signals and their representation as a sum of harmonically related sinusoids.

-- Implementing a multiplier for rectified signals, aligning square waves with cosine waves using calculated delays, and plotting error signals between a square wave and its harmonic approximations.

Lab 2: Modulation & Message Recovery

Introduction to Double-Sideband Suppressed Carrier (DSB-SC) modulation.

-- Analyzing Fourier Transforms of carrier signals and implementing a message recovery system using a low-pass filter (LPF) and a second mixer to isolate baseband signals.

Lab 3: First SDR Experiments

Practical application of software-defined radio to analyze real-world signals.

-- Monitoring FM broadcast bands (88MHz-108MHz), applying Carson's Rule for bandwidth estimation, and identifying local NOAA weather radio stations (e.g., KHB39 Jacksonville) using SDR++.

Lab 4: AM Modulation Comparison

A comparative study of different Amplitude Modulation (AM) detection methods.

-- Evaluating DSB-SC correlation receivers, standard AM envelope detectors, and squaring receivers. Findings focused on the trade-offs between audio fidelity and hardware simplicity.

Lab 5: Quadrature-Based Envelope Detection

Implementation of a robust AM receiver that does not require carrier phase recovery.

-- -Developing I and Q arm mixers (Quadrature) in GNU Radio, using DC blockers, and applying rational resamplers to prepare signals for audio sinks.

Lab 6: Quadrature Amplitude Modulation (QAM)

Analysis of high-spectral efficiency digital modulation.

-- Investigating 16, 64, and 256-QAM states, simulating phase shifts (45∘, 90∘, 180∘), and observing the resulting rotations in the signal constellation plot.

Lab 7: FM Demodulator & Differentiators

Design and verification of frequency modulation recovery systems.

-- Using a Decimating FIR Filter as a discrete differentiator to approximate dx/dt. Verified the system by converting a triangle wave input into a square wave output.

Lab 8: Phase-Locked Loops (PLL)

Study of synchronization and frequency tracking.

-- Calculating instantaneous frequency error, determining loop bandwidth requirements for locking onto modulated carriers, and analyzing the impact of noise on PLL stability.

Lab 9: Stereo FM Receiver

-- The culmination of modulation theory into a fully functional stereo broadcast receiver.

    Key Tasks: Implementing pre-emphasis/de-emphasis for SNR improvement, decoding L+R (mono) and L-R (stereo subcarrier) signals, and isolating the 19 kHz pilot tone for coherent DSB-SC demodulation of the stereo channel.