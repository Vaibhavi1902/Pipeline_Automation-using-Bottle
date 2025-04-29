# Pipeline_Automation-using-Bottle
Bioinformatics Nextflow pipeline automation using Bottle (Python micro framework)
This project provides a lightweight and automated pipeline for running [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) quality control on high-throughput sequencing data. It integrates **Nextflow** for scalable workflow execution and **Bottle (Python micro-framework)** for providing a simple web interface.
Features

-  Automates FastQC analysis on multiple `.fastq` files
-  Built using [Nextflow](https://www.nextflow.io/) for reproducible and parallel execution
- Bottle-based Python web server for:
- Uploading sequence files
- Triggering analysis
- Viewing or downloading results
- Generates HTML and summary reports per sample
