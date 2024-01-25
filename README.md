# **ColabFold-Pipeline-Toolkit**

<p align="center"><img src="https://github.com/andyposbe/ColabFold-Pipeline-Toolkit/blob/main/Overview.png" height="420"/></p>


The aim of this repository is to provide simple tools to help those working with ColabFold BATCH both for pre and post-processing steps.

## Notebooks
- Pre-Processing: [Pre-Processing Toolkit](https://github.com/andyposbe/ColabFold-Pipeline-Toolkit/blob/main/Pre_processing.ipynb)
- Post-Processing: [ColabFold BATCH Score Extractor](https://colab.research.google.com/github/andyposbe/ColabFold-Pipeline-Toolkit/blob/main/Score_Extractor.ipynb)

## Description

This repository is dedicated to providing resources and tools to facilitate screens with ColabFold BATCH pipelines. Here, you will find a collection of Google Colab notebooks that are designed to simplify and automate the pre-processing and post-processing steps in protein structure prediction using ColabFold and ColabFold BATCH.

## Features

- **Pre-Processing Toolkit**: Scripts to prepare your data for processing with ColabFold, including:
  1. **Fasta combiner for AF2-Multimer**. Two lists of fastas may be combined for 2-way AlphaFold-Multimer screens. Interactive selection menus in the notebook allow for sub-selections from either pool of fasta files.
  2.  **Homo-multimer fasta preparation**. Preparation of homo-oligomer fasta files from simple monomer fasta files.
  3. **Multifasta demultiplexer.** Converts multifasta into individual fasta files, compatible with ColabFold BATCH.
 
- **ColabFold BATCH Score Extractor**:
  1. Filtering for highest_ranked models
  2. pTM and max_pae extraction
  3. ipTM extraction and model confidence calculation
  4. Dataframe output
  5. Static and interactive plot generation
   
## **Tutorials**: Step-by-step guides on how to use these notebooks effectively. *(coming soon)*

## **FAQs**: Answers to common questions and troubleshooting tips. *(in development)*

## Getting Started

1. **Prerequisites**: Ensure you have a Google account and access to Google Colab.
2. **Installation**: No installation needed, just copy the desired notebooks.

## How to Use

- **Accessing Notebooks**: Direct links to the Google Colab notebooks are provided. Simply click on a link to open a notebook in Google Colab.
- **Running Notebooks**: Follow the instructions within each notebook to execute the pre-processing or post-processing steps.

## Acknowledgments


## How do I reference this work?

## Contact

For questions and feedback, please contact [Andrés Posbeyikian] at [andres.posbeyikian@tsl.ac.uk].
