# Threatora Utility & Dataset Ingestion Scripts

Automation scripts for data ingestion, feature extraction, offline model training, and integration testing.

## Key Scripts

- `setup_dataset.py`: Automated download and verification of CTU-13 telemetry captures.
- `extract_binetflow.py`: Parses raw BiNetFlow files into tabular flow records.
- `flow/build_balanced_train.py`: Prepares balanced training windows for LSTM RSSM.
- `flow/train_flow_world_model.py`: Multi-epoch training harness with validation checkpointing.
- `test_upload_csv.py`: Simulates continuous PCAP/CSV telemetry ingestion to the live API.
