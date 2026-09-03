# Boltz Structure Prediction Demo

A simple demo using [Boltz-2](https://github.com/jwohlwend/boltz) to predict the structure of a protein sequence pulled from UniProt.

## Setup

Install the environment with conda:

```bash
conda create -f environment.yml && conda activate boltz
```

## Usage

Launch Jupyter and run `boltz_demo.ipynb` top to bottom:

```bash
jupyter notebook boltz_demo.ipynb
```

Outputs (input YAML, predicted structure, etc) are written to the `output/` directory.
