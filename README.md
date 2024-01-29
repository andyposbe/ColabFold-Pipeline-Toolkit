# **ColabFold-Pipeline-Toolkit** 

<p align="center"><img src="https://github.com/andyposbe/ColabFold-Pipeline-Toolkit/blob/main/Overview.png" height="420"/></p>

The **ColabFold-Pipeline-Toolkit** serves as a streamlined resource for enhancing the protein structure prediction process with [ColabFold](https://github.com/sokrypton/ColabFold), a tool that democratizes access to the groundbreaking AlphaFold2 technology through Google Colab. Recognizing the challenges faced by researchers, especially those with less specialization in computational biology, in preparing and analyzing large datasets for high-throughput screens using ColabFold's BATCH notebook, this toolkit offers a suite of Google Colab Notebooks. These notebooks are seamlessly integrated with Google Drive directories, providing user-friendly pre-processing and post-processing capabilities to simplify the workflow for scientists.

## Notebooks
- Pre-Processing: [Pre-Processing Toolkit](https://colab.research.google.com/github/andyposbe/ColabFold-Pipeline-Toolkit/blob/main/Pre_processing.ipynb)
- Post-Processing: [ColabFold BATCH Score Extractor](https://colab.research.google.com/github/andyposbe/ColabFold-Pipeline-Toolkit/blob/main/Score_Extractor.ipynb)

## Description

This repository is dedicated to providing resources and tools to facilitate screens with ColabFold BATCH pipelines. Here, you will find a collection of Google Colab notebooks that are designed to simplify and automate the pre-processing and post-processing steps in protein structure prediction using ColabFold and ColabFold BATCH.

## Features

- **Pre-Processing Toolkit**: Scripts to prepare your data for processing with ColabFold, including:
  1. **Fasta combiner for AF2-Multimer**. Two lists of fastas may be combined for 2-way AlphaFold-Multimer screens. Interactive selection menus in the notebook allow for sub-selections from either pool of fasta files.
  2.  **Homo-oligomer fasta preparation**. Preparation of homo-oligomer fasta files from simple monomer fasta files.
  3. **Multifasta demultiplexer.** Converts multifasta into individual fasta files, compatible with ColabFold BATCH.
 
- **ColabFold BATCH Score Extractor**:
  1. Filtering for highest_ranked models
  2. pTM and max_pae extraction
  3. ipTM extraction and model confidence calculation
  4. Dataframe output
  5. Static and interactive plot generation

## Getting Started

- **Prerequisites**: Ensure you have a Google account and access to Google Colab.
- **Installation**: No installation needed, just copy the desired notebooks.

## How to Use
- **Accessing Notebooks**: Direct links to the Google Colab notebooks are provided. Simply click on a link to open a notebook in Google Colab.
- **Running Notebooks**: Follow the instructions within each notebook to execute the pre-processing or post-processing steps.

## Acknowledgments
- [Highly accurate protein structure prediction with AlphaFold](https://doi.org/10.1038/s41586-021-03819-2), Jumper, J., Evans, R., Pritzel, A. et al. Nature 596, 583–589 (2021).
- [ColabFold: making protein folding accessible to all](https://www.nature.com/articles/s41592-022-01488-1), Mirdita, M., Schütze, K., Moriwaki, Y. et al. ColabFold: making protein folding accessible to all. Nat Methods 19, 679–682 (2022).
- I thank my colleagues at The Sainsbury Laboratory for their support and encouragement.


## How do I reference this toolkit?
If you use this toolkit, please cite as follows:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10568700.svg)](https://doi.org/10.5281/zenodo.10568700)
```python
@Article{ColabFold-Pipeline-Toolkit,
  author  = {Posbeyikian A., Kamoun S.},
  journal = {Zenodo},
  title   = {ColabFold-Pipeline-Toolkit},
  year    = {2024},
  doi     = {https://doi.org/10.5281/zenodo.10568700}
}
```
## Contact
For questions and feedback, please contact [Andrés Posbeyikian] at [andres.posbeyikian@tsl.ac.uk].
