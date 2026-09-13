# Threatora Model Checkpoints & Artifacts

This directory contains trained model weights, feature scalers, and telemetry statistical baselines for the **Threatora Dual World Model** architecture (NTRO PS 26153).

## Directory Structure

- `checkpoints/flow/`
  - `ciciot_lstm_world_model_fast_best.pt`: PyTorch checkpoint for Flow World Model (LSTM state-space predictor).
  - `feature_statistics.json`: Normalization baselines and feature scaling parameters.
  - `scaler.pkl`: Serialized scikit-learn standard scaler for flow feature vectors.

- `checkpoints/packet/`
  - `packet_lstm_world_model_best.pt`: PyTorch checkpoint for Packet World Model (packet-level temporal dynamics).
  - `scaler.pkl`: Serialized scaler for packet-level window metrics.

All checkpoints are optimized for CPU and CUDA inference with lazy singleton loading.
