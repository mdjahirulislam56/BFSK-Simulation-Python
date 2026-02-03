# BFSK Simulation and Performance Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview
This project implements a **Binary Frequency Shift Keying (BFSK)** communication system using Python. It simulates the transmission of digital data through an **Additive White Gaussian Noise (AWGN)** channel and evaluates the system's performance using **Non-Coherent Detection**.

The simulation includes:
- Signal modulation (BFSK).
- Channel simulation (AWGN with varying SNR levels).
- Demodulation (Non-coherent detection).
- Bit Error Rate (BER) calculation and analysis.
- Visualization of carrier signals, modulated signals, and demodulated output.

## Features
* **Modulation:** Generates BFSK signals with configurable carrier frequencies ($f_0$ and $f_1$).
* **Channel Model:** Simulates real-world noise using an AWGN channel.
* **Demodulation:** Implements non-coherent detection (envelope detection) which does not require phase synchronization.
* **Performance Metrics:** Calculates and prints the number of bit errors for different SNR (Signal-to-Noise Ratio) values.
* **Visualization:** Uses `matplotlib` to plot:
    * Binary input data.
    * Carrier signals.
    * Modulated signal in the time domain.
    * Received signal with noise.
    * Demodulated binary stream.

## Technologies Used
* **Python**
* **NumPy:** For numerical operations and signal generation.
* **SciPy:** For signal processing utilities.
* **Matplotlib:** For plotting waveforms and results.
* **Pandas:** For data handling.

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/mdjahirulislam56/BFSK-Simulation-Python.git](https://github.com/mdjahirulislam56/BFSK-Simulation-Python.git)
