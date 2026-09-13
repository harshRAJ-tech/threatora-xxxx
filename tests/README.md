# Threatora Automated Test Suite

Unit, integration, and end-to-end test suites for Threatora (NTRO PS 26153).

## Test Modules

- `test_dual_world_model.py`: Validates model inference, multi-horizon trajectory forecasting, and fusion mechanics.
- `test_system_integration.py`: Validates REST API endpoints, Zero-Trust authorization headers, and containment triggers.

## Running Tests

Execute test suites via pytest:
```bash
pytest tests/ -v
```
