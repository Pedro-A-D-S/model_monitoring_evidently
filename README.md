# Evidently AI Monitoring for ML Activities

## Overview

This repository contains the necessary files and notebooks to perform monitoring activities for machine learning models using Evidently AI. The monitoring focuses on assessing machine learning model quality, data quality, and detecting data drift.

## Project Structure

```
├── notebooks
├── poetry.lock
├── pyproject.toml
├── reports
├── source
└── tests
```

- **notebooks**: This directory contains Jupyter notebooks for different monitoring tasks.

- **poetry.lock, pyproject.toml**: Files related to managing project dependencies usingPoetry.

- **reports**: Generated HTML reports for monitoring results.

- **source**: Placeholder for source code related to monitoring activities.

- **tests**: Directory for testing scripts related to monitoring.

## Getting Started

1. Clone this repository:
``` bash
git clone https://github.com/Pedro-A-D-S/model_monitoring_evidently.git
```

2. Install project dependencies:
``` bash

poetry env use python3.10
poetry shell
poetry install
```
3. Open and run the Jupyter notebooks in the `notebooks` directory to perform monitoring tasks.

## Usage
- Execute the notebooks in the specified order for comprehensive monitoring of ML activities.
- Refer to the generated reports in the reports directory for detailed insights into model and data quality.

## Contributing

Feel free to contribute by opening issues, providing feedback, or submitting pull requests.