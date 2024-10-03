# Building a Ransomware Simulator

This repository contains the code for a ransomware simulator developed during the **CYBER GYAN VIRTUAL INTERNSHIP PROGRAM** at **Centre for Development of Advanced Computing (CDAC) Noida**.

## Project Overview

The project aims to develop a ransomware simulator that mimics the behavior of actual ransomware without causing any harm. The simulator encrypts test files, displays a ransom note, and simulates disabling functionalities to test security measures and user awareness.

### Key Features
- **File Encryption/Decryption**: The simulator encrypts files using symmetric encryption (AES) and renames them to show their encrypted state.
- **Ransom Note GUI**: A graphical window displays the ransom message with a countdown timer and fields for the decryption key.
- **Non-Destructive**: The encryption and decryption operations are reversible to prevent data loss.

## Tools and Technologies Used

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - **Cryptography**: `PyCryptodome` for encryption and decryption
  - **File Manipulation**: `os` and `shutil` for file and directory operations
  - **GUI Development**: `Tkinter` for building the ransom note window
  - **Image Processing**: `Pillow` for image handling in the GUI
- **Development Environment**: Visual Studio Code (VS Code)

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ransomeware_simulation.git
   cd ransomeware_simulation
