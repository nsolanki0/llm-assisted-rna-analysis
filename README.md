# LLM-Assisted RNA Analysis

A collection of R Markdown workflows and task-oriented examples for bulk and sc-RNA seq data analysis, intended to support the development and evaluation of LLM-assisted scientific data analysis and visualization.

## Overview
This repository contains a collection of R Markdown (.Rmd) files covering a range of common tasks and workflows in bulk and single-celled RNA seq data analysis.

The examples include:

- RNA-seq and gene expression analysis
- Single-cell RNA-seq (scRNA-seq)
- DNA methylation analysis
- Data wrangling and preprocessing
- Statistical analysis and machine learning
- Data visualization
- Classification and regression
- Feature selection
- Cell-type annotation and reference-based analysis

The repository currently consists primarily of workflow-oriented R Markdown files. Each workflow can contain multiple tasks, ranging from small, focused operations to complete analysis workflows.

## Repository structure

```text
llm-assisted-rna-analysis/
├── README.md
├── workflows/
│   ├── WF01.Rmd
│   ├── WF02.Rmd
│   ├── WF03.Rmd
│   └── ...
├── LICENSE
└── .gitignore
```

## Workflow format
Each R Markdown workflow contains a number of task examples. A typical task consists of:

1. A task description and metadata
2. A natural-language prompt
3. An explanation/completion
4. R code illustrating the solution

For example:

```text
### Task ...

prompt:
...

completion:
...

```{r,eval=FALSE}
...
```

--- TASK END

The tasks vary in size and complexity. Some address a single operation, while others combine several analysis steps into a larger workflow.

## Purpose

The workflows were assembled from a combination of:

- Textbooks and educational materials
- Package and software documentation
- Publicly available examples
- Publicly available biological datasets
- Existing analysis workflows

The task prompts and explanatory/completion text were developed as part of the construction of this collection.

The repository is intended to provide a structured collection of realistic biological data-analysis problems and corresponding R-based solutions that can potentially be used for LLM-assisted analysis, benchmarking, evaluation, or further development.

## Data, software, and third-party material

Many workflows use established R/Bioconductor packages, annotation resources, published datasets, and other publicly available resources.

Examples may include resources such as:

- Bioconductor packages and datasets
- Public RNA-seq and single-cell RNA-seq datasets
- MSigDB gene sets
- Annotation databases and resources
- Published biological datasets

These resources are **not owned by this repository** and may have their own licenses, terms of use, attribution requirements, or citation requirements.

Where appropriate, the relevant packages, datasets, references, and external resources should be consulted for their original licensing and citation information.

## Reproducibility

The R code in the workflows is provided as analysis examples. Exact results may depend on:

- R and package versions
- Availability and versions of external annotation resources
- Dataset versions
- Changes in software APIs
- Random seeds and computational environment

The workflows should therefore be regarded as reproducible examples rather than guaranteed bit-for-bit reproducible computational environments.

## Status

This repository is under development.

The initial version preserves the original R Markdown workflows as individual files. Further organization, documentation, metadata, and automated extraction of individual tasks may be added as the project develops.

## License

See the [`LICENSE`](LICENSE) file for the license applicable to the original material in this repository.

Third-party datasets, software, examples, and other external resources remain subject to their respective licenses and terms of use.
