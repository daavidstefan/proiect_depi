# 🔐 BER Estimation in Encrypted Channels

This project aims to visualize and analyze the relationship between Bit Error Rate (BER) and Signal-to-Noise Ratio (SNR) in encrypted communication channels using an interactive MATLAB application.

# 📌 Overview

Instead of a simple script, we designed a user-friendly graphical application that simulates the full transmission process of a binary signal through a noisy channel, including encryption and decryption steps.

# Main Features:
- GUI built with MATLAB App Designer
- Real-time visualization of BER vs. SNR
- XOR-based encryption/decryption
- Simulation of AWGN (Additive White Gaussian Noise)
- Modulation and demodulation stages
- Parameter control (SNR, key, bitstream length)

# ⚙️ How It Works

1. **Bitstream Generation**: Random binary sequence is created.
2. **Encryption**: Signal is encrypted using a simple XOR operation with a key.
3. **Modulation**: Encrypted bits are modulated for transmission.
4. **Noise Injection**: AWGN is added to simulate real transmission conditions.
5. **Demodulation**: Noisy signal is demodulated.
6. **Decryption**: Original bits are recovered using the same XOR key.
7. **BER Calculation**: BER is computed by comparing the transmitted and received bits.

# 📊 Results

- As **SNR increases**, the **BER drops exponentially**, approaching zero.
- In noisy environments (low SNR), the BER approaches 0.5, meaning nearly half of the bits are received in error.
