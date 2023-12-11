The development of this tool followed a methodical and structured approach across various phases. Initially, a requirements analysis was conducted to fully understand the scope of the cyber threat and 
the required functionalities of the simulator. Subsequently, an architecture was developed by identifying the involved components and their relationships. A "target machine" was defined as the point of 
origin for the attack, while a "server machine" was designed to generate the necessary cryptographic datasets and manage the fundamental parameters used in the encryption process.

To simulate the spread of the ransomware, two additional components were integrated into the system, allowing for the assessment of the virus propagation effectiveness. 
The development process was guided by the design phase, outlining the architecture and functionalities, followed by the actual implementation of cryptographic mechanisms.
In the final phase, the system was simulated in a scenario to verify its correct operation and compare it with known ransomware in the market.

##  Technology Used
- Rust
- PsExec
- Visual Studio Code
- Python
- Active Directory

# Cryptography 
- AES 128-256 mode counter or cbc
- RSA 2048
