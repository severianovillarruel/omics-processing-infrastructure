# Modular WDL pipeline for cell-free DNA methylation analysis.

## Background & Slide Deck

The work showcased:

**Slide Deck**
- [![Slide preview](slides/wdlPreview.png)](slides/InfrastructurePresentation.pdf)
- [WDL Project](https://github.com/openwdl)

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
