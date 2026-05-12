BPSK BER Analysis
Overview

This project presents the implementation and performance analysis of Binary Phase Shift Keying (BPSK) modulation using MATLAB.

Different channel coding techniques were implemented and tested over AWGN and Rayleigh channels to evaluate the Bit Error Rate (BER) performance of digital communication systems.

The project also compares different decoding methods and modulation schemes to analyze communication reliability under noisy channel conditions.

Features
BPSK Modulation and Demodulation
AWGN Channel Simulation
Rayleigh Fading Channel Simulation
BER Performance Analysis
Repetition-3 and Repetition-5 Coding
Hard Decision Decoding
Soft Decision Decoding
Hamming (7,4) and Hamming (15,11) Codes
BPSK vs QPSK Comparison
BER vs Eb/N0 Performance Curves
Technologies Used
MATLAB
Digital Communication Theory
Channel Coding Techniques
BER Analysis
Project Structure
Requirement 1 — Uncoded BPSK Performance
Generate random binary data
Apply BPSK modulation
Transmit through AWGN channel
Calculate BER
Compare simulated and theoretical BER
Requirement 2 — BPSK with Repetition-3 Coding
Repetition coding implementation
Hard Decision decoding
Soft Decision decoding
BER performance comparison
Requirement 3 — BPSK with Repetition-5 Coding
Repetition-5 coding
Majority voting decoding
BER analysis for different energy cases
Hard vs Soft Decision comparison
Requirement 4 — Hamming Codes
Hamming (7,4) implementation
Hamming (15,11) implementation
Error correction capability analysis
BER performance evaluation
Bonus Work
Rayleigh Channel Simulation
BPSK over Rayleigh fading channel
Channel equalization
BER analysis under fading conditions
BPSK vs QPSK Comparison
BER comparison over AWGN channel
Modulation efficiency analysis
Bandwidth efficiency comparison
Results
BER decreases as Eb/N0 increases.
Channel coding significantly improves communication reliability.
Soft Decision decoding achieves better BER performance than Hard Decision decoding.
Hamming codes provide better efficiency compared to repetition codes.
AWGN channel performs better than Rayleigh fading channel.
BPSK achieves lower BER while QPSK provides higher bandwidth efficiency.
Conclusion

This project demonstrates the importance of channel coding in digital communication systems.

Different coding techniques were analyzed using MATLAB simulations, showing significant improvements in BER performance and transmission reliability under noisy channel conditions
