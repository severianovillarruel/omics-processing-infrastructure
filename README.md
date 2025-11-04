# Modular WDL pipeline for cell-free DNA methylation analysis.

## Background & Slide Deck

The work showcased:

**Slide Deck**
- [WDL Infra Presentation](https://docs.google.com/presentation/d/1LIXpHik8NLAWx9rh3QRDprqkcYSBqIQvtPnO5wYIg2k/edit?usp=sharing)

**Features**
- Parallelized WDL tasks for QC, mapping, and methylation calling
- Synthetic input data for demonstration
- Cromwell-compatible and containerized (Singularity)
- Designed for easy extension to other cfDNA or methylation datasets

**Overview**
![Pipeline overview](docs/pipeline_diagram.png)

**Quickstart**
```bash
cromwell run workflow/main.wdl --inputs config/inputs.json
```
