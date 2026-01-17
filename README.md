# C. elegans Promoter Library Design Pipeline

**Master's Thesis Project** **Author:** Mian Mashaal Ahmad 
**Institution:** King Abdullah University of Science and Technology (KAUST)  
**Lab:** Laboratory of Synthetic Genome Biology 

## Overview
This repository contains the computational pipeline used to design promoter libraries for *C. elegans*. The tool automates the extraction of upstream promoter sequences, segments them into synthesis-ready windows, and patches BsaI restriction sites for Golden Gate assembly compatibility.

## Contents
* `Sequence_Extraction.ipynb`: The main Jupyter Notebook for the pipeline.
* `gene_set.csv`: List of target genes used in the study.
* `requirements.txt`: List of Python dependencies.

## Usage
1. Download the *C. elegans* genome (WS297) FASTA and GFF3 files.
2. Place them in the root directory.
3. Run the notebook `Sequence_Extraction.ipynb`.

## Requirements
* Python 3.10+
* Biopython
* Pandas
