# Prolific Survey Getting Started (API Demo)

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Status: Beta](https://img.shields.io/badge/Status-Beta-orange.svg)]()
[![Purpose: Educational](https://img.shields.io/badge/Purpose-Educational-green.svg)]()

A minimal, end-to-end example showing how to programmatically create, publish, and analyze a survey on Prolific using the API.

This repository is designed as a getting-started demo for researchers, engineers, and AI/ML practitioners who want to collect high-quality human responses using Prolific.

## Files

- **`config.yaml`** - Survey configuration (questions, rewards, participant settings)
- **`prolific_helpers.py`** - Helper functions for Prolific API interactions
- **`prolific-survey-getting-started.ipynb`** - Main notebook workflow
- **`environment.yaml`** - Conda environment specification
- **`.env.example`** - Template for environment variables

## Setup

1. Copy `.env.example` to `.env` and add your credentials:
   ```bash
   cp .env.example .env
   ```

2. Install dependencies using conda (recommended) or pip:

   **Option A: Using conda**
   ```bash
   conda env create -f environment.yaml
   conda activate prolific-demo
   ```

   **Option B: Using pip**
   ```bash
   pip install pandas matplotlib pyyaml requests python-dotenv
   ```

## Usage

1. Edit `config.yaml` to customize your study
2. Run the notebook to create and publish your survey
3. View results with demographic breakdowns (generation, gender)

## Features

- Create surveys and studies via Prolific API
- Auto-publish and monitor submissions
- Visualize results by demographics
- Export data to CSV


## About Prolific

Prolific connects AI researchers and developers with high-quality human data. Source large samples of domain experts, experienced AI trainers, and diverse demographics in hours, not weeks.

**Self-service** or **full-service** — your choice.

---

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## Important Notice

> This project is provided **as-is** for **educational and research purposes only**.
> - 🔬 **Beta Status**: This is experimental code and may contain bugs or incomplete features
> - 📚 **Not Maintained**: No active development or support is provided
> - 🎓 **Educational Use**: Intended as a learning resource for RLHF workflows
> - ⚖️ **Use at Your Own Risk**: Test thoroughly before using in production environments
