# Vault Password Lock
Using an FPGA board, lock, unlock, and set a password to a vault like mechanism. <br/>

I used an DE10-Lite for this project.<br/>

Compiled on Quartus Prime 24.1

## How it Works 🚀
- Has 4 States
  * State 1 is Open Frozen: Moves to State 2 once KEY is let go
  * State 2 is Open Free: sets password to whatever the switches are KEY is pressed and moves to State 3
  * State 3 is Closed Frozen: Moves to State 4 once KEY is let go
  * State 4 is Closed Free: Checks if password is correct when KEY is pressed and moves to State 1 if so

## Tech Stack 🛠️
100% System Verilog

# Contact 📬
Created by Owen Anderson on Oct 22, 2025
