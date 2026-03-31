
John the Ripper: Password Auditing and Security Tool Implementation
Overview
John the Ripper (JtR) is a versatile, open-source password security auditing and recovery tool. This project demonstrates its core functionalities in identifying weak credentials by decrypting various hash values into plaintext. It covers the tool's application across different platforms and its integration into automated security workflows.

Objectives
To demonstrate the effectiveness of multiple password recovery techniques including Dictionary, Brute Force, and Hybrid attacks.

To evaluate performance optimizations such as multiprocessing (fork implementation) and hardware acceleration.

To implement a programmatic automation of cracking workflows using a custom Python script.

To audit the security of system hashes and encrypted archive files (e.g., ZIP).

Key Features

Automatic Hash Detection: Seamlessly identifies diverse encryption algorithms like MD5, SHA-1, NTLM, and bcrypt. 


Diverse Cracking Modes: Implements Single Crack, Wordlist (Dictionary), and Incremental (Exhaustive) modes. 


Archive Support: Extends recovery capabilities to encrypted ZIP and RAR archive formats. 


Performance Scaling: Leverages multi-core CPU processing and GPU acceleration (OpenCL/CUDA) for large-scale operations. 


Extensibility: Supports custom rule-based attacks, third-party plugins, and Graphical User Interface (GUI) management
