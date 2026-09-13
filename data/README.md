# Threatora Datasets & Traffic Telemetry

This directory hosts raw and processed network traffic telemetry, benign baseline profiles, and multi-stage attack scenarios for Threatora (NTRO PS 26153).

## Data Layers

- `raw/`: Raw packet captures (PCAP) and NetFlow logs from CTU-13 and CIC-IoT2023 datasets.
- `processed/`: 60-second windowed feature tensors stored in high-performance Parquet format (`scenario_01.parquet` through `scenario_13.parquet`).
- `samples/`: Verified attack samples including lateral movement, beaconing, and exfiltration bursts (`host-becomes-infected.csv`, `sample_traffic.csv`).

All telemetry adheres to the 62-dimensional state-space feature definition described in the technical architecture documentation.
