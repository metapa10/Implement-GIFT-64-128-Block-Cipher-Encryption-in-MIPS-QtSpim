GIFT-64-128 Block Cipher Encryption in MIPS QtSpim

This repository contains an implementation of the GIFT-64-128 block cipher encryption algorithm in MIPS assembly language using the QtSpim MIPS assembler and simulator.
Objective

The main objectives of this project are:

    Learn the features of the MIPS architecture and instruction set architecture (ISA).
    Gain proficiency in using the QtSPIM MIPS Assembler and Simulator.
    Implement cryptographic block ciphers in MIPS assembly language, specifically the GIFT-64-128 algorithm.

Preparation

Before you start, ensure that you have:

    Installed and tested the QtSpim MIPS assembler and simulator.
    Reviewed the preparatory materials provided in the course content related to GIFT-64-128.

Project Overview

This project focuses on implementing one round of block encryption using the GIFT-64-128 algorithm. The algorithm processes a 64-bit input plaintext (PT) using a fixed 128-bit secret key (K) and produces a 64-bit output ciphertext (CT). The encryption process involves SubCells, PermBits, and AddRoundKey transactions, which are repeated across 28 rounds. The KeySchedule algorithm is used to update the key at the end of each round.
Instructions

    Clone this repository to your local machine.
    Open the QtSpim MIPS assembler and simulator.
    Load the provided assembly program file.
    Run the simulation to observe the encryption process.

Memory Convention

Please adhere to the following memory convention for successful execution:

    Plaintext (PT) and Key (K) values are read in little-endian byte order.
    Use the provided memory directives in your assembly program for loading PT and K values.

Note

The provided PT and K values are presented in both hexadecimal and little-endian byte order representations. Ensure your program handles these representations correctly.
Disclaimer

This implementation is for educational purposes and follows the GIFT-64-128 algorithm's specifications. It is important to note that the actual security of cryptographic algorithms requires rigorous analysis and validation.
Acknowledgments

The GIFT-64-128 algorithm is described in S. Banik et al.'s paper "GIFT: A Small Present Towards Reaching the Limit of Lightweight Encryption." The full reference is available in the course content.
