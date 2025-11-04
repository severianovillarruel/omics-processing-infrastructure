# cfDNA Methylation Pipeline
Modular WDL pipeline for cell-free DNA methylation analysis.

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
