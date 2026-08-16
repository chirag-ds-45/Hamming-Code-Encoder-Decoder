# (7,4) Hamming Code Encoder and Decoder with Single-Bit Error Correction

## Project Overview

This project implements a (7,4) Hamming Code based error detection and correction system. The system encodes 4-bit data into a 7-bit codeword by adding three parity bits and is designed to detect and correct a single-bit error in the received codeword.

The project was implemented and tested using both MATLAB simulation and hardware logic circuits.

## Objectives

- Implement (7,4) Hamming Code encoding and decoding.
- Generate parity bits for a 4-bit data input.
- Detect a single-bit error using syndrome calculation.
- Identify the position of the corrupted bit.
- Correct the detected single-bit error.
- Verify the corrected data using MATLAB simulation and hardware implementation.

## How It Works

The system follows these main steps:

1. A 4-bit data input is provided to the encoder.
2. Three parity bits are calculated and added to form a 7-bit Hamming codeword.
3. A single-bit error can be introduced into the transmitted codeword.
4. The receiver calculates the syndrome from the received codeword.
5. The syndrome identifies the position of the erroneous bit.
6. The identified bit is corrected.
7. The original 4-bit data is recovered from the corrected codeword.

## MATLAB Implementation

MATLAB was used to simulate the encoding, error insertion, syndrome calculation, error correction, and decoding process.

The simulation demonstrates the detection and correction of a single-bit error in a 7-bit Hamming codeword.

## Hardware Implementation

The hardware implementation uses digital logic components to demonstrate the Hamming Code encoder and decoder.

### Components Used

- 7486 XOR Gate IC
- 74138 Decoder IC
- DIP Switches
- LEDs
- Breadboard
- Resistors
- 5V regulated power supply
- Jumper wires

## Project Structure

```text
MATLAB/
    hamming_code.m

Hardware/
    project-photo.jpg
    encoder-diagram.png
    decoder-diagram.png

Results/
    matlab-output.png
