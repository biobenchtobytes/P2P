# NeuroSync Research Codebase

A Python toolkit for analyzing ***neural synchronization patterns*** in multi-electrode recordings.

## Features

- Real-time synchronization detection
- Multi-channel signal processing
- Statistical validation framework
- Visualization utilities

## Requirements & Installation

This codebase requires python >3.12. Additional requirements are listed in the `environment.yml`, which can be used to generate a standalone conda environment containing neurosync.

Alternatively, to install neurosync independently:

```bash
pip install neurosync
```

## Quick Start

```python
from neurosync import Analyzer

analyzer = Analyzer(sample_rate=30000)
sync_data = analyzer.detect_patterns(recording)
analyzer.plot_results(sync_data)
```

## Citation

If you use NeuroSync, please cite: `Smith J, Doe J (2024) NeuroSync as a method for analysing multielectrode recordings. bioRxiv doi: 10.6758/2026.01.01.101010v1`

