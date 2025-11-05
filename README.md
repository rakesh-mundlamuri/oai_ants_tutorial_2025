# TUT1: Innovation and Prototyping with Open RAN Testbeds
Welcome to our IEEE ANTS 2025 tutorial! 
To participate in the OpenAirInterface (OAI) hands-on session, participants may bring their own laptop with OAI already installed (see instructions below) or can use the cloud access provided by the tutorial organizers. 
In either case, all participant MUST bring their own laptop that has access to internet.

## 1. Minimum Computing Requirements
To run an end-to-end 5G network with OAI Core Network (CN),
Radio Access Network (RAN) including base station (gNB) and user equipment (nrUE) in RFsim mode, we need the following minimum recommended computing requirements: 
-  Operating System: Ubuntu 22.04 LTS
-  CPU: 8 virtual cores x86_64 @ 3.5 GHz
-  RAM: 16 GB
  
You can use your own laptop if it fulfils the above requirments, or you will be provided with a Virtual Machine (VM) in a cloud platform.

## 1. Environment Setup

To setup OAI, please follow these instrunctions in the order they appear:

1. Install the required software using [utils/Util_Installation.md](./utils/Util_Installation.md) in your computer or VM.
2. Install the OAI CN by following the instructions at [cn/CN_Installation.md](./cn/CN_Installation.md)
3. Finally, install the RAN using the instructions at [ran/RAN_Installation.md](./ran/RAN_Installation.md)
