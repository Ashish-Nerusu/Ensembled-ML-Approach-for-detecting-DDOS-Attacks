# Ensembled-ML-Approach-for-detecting-DDOS-Attacks
**I am currently working on this project**
This project focuses on enhancing Network Security in a Software Defined Networking (SDN) environment through the detection of Distributed Denial of Service (DDoS) attacks using Machine Learning (ML) techniques. Built on a simulation stack using Mininet, Ryu controller, and custom traffic generators, this system integrates ML models to detect malicious patterns in network traffic in real time.

🧩 Key Components
SDN Simulation: Emulated using Mininet with a topology of switches and hosts.

Ryu Controller: Used to monitor and control the network flow.

Traffic Generation:

Scapy and hping3 for simulating DDoS attacks.

iperf for generating legitimate traffic.

Dataset Creation: Extracted flow-level statistics from the controller and stored in CSV format.

Machine Learning Models:

Random Forest, Gradient Boosting, XGBoost, etc.

Evaluation metrics: Accuracy, Precision, Recall, F1-score

DDoS Detection: Real-time classification of normal vs malicious flows.

