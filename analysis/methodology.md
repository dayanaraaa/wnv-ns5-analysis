# Methodology Overview

## Project Context

This project was completed as part of an undergraduate research course and training program at Florida International University. The research reported in this presentation was supported by the National
Institutes of Health under award number R25AI170382. The content is solely the responsibility
of the authors and does not necessarily represent the views of the NIH.

The work explored promising druggable pockets within the NS5 protein of West Nile Virus as potential antiviral targets with broader implications for flavivirus therapeutics.

## Research Question

Which NS5 protein pockets exhibit the most favorable characteristics for future antiviral drug development, considering evolutionary conservation, structural confidence, and intrinsic disorder?

## Computational Methods

The project utilized the following bioinformatics tools:

- BLAST for sequence retrieval
- MUSCLE (via Jalview) for multiple sequence alignment
- IQ-TREE for phylogenetic reconstruction
- Rate4Site for evolutionary-rate estimation
- AlphaFold/ColabFold for protein structure prediction
- IUPred for disorder prediction
- PockDrug for pocket identification and druggability assessment
- PyMOL for structural visualization
- SQL databases for residue-level organization and analysis

## Reproducibility Statement

The computational scripts and analysis pipelines used during the course were developed and maintained by the instructional program and are therefore not included in this repository.

This repository serves as an archive of educational outputs, figures, reports, and presentation materials generated during the project.

## Key Findings

Two pockets (Pocket 0 and Pocket 4) emerged as the most promising antiviral targets due to:

- Low evolutionary rates
- High AlphaFold confidence scores
- Low intrinsic disorder
- Favorable structural accessibility
- Large residue compositions suitable for molecular binding


### WNV_database.xlsx
An integrated residue-level dataset assembled by the author using course methodologies and instructions.

The spreadsheet combines:
- Residue numbering and amino acid identities
- AlphaFold confidence (pLDDT) scores
- Secondary structure assignments
- IUPred disorder predictions
- ANCHOR scores
- Candidate pocket annotations
