# LLM-Assisted RNA Analysis

A collection of R Markdown workflows and task-oriented examples for bulk RNA-seq and single-cell RNA-seq data analysis, intended to support the development and evaluation of LLM-assisted scientific data analysis and visualization.

## Overview
This repository contains a collection of R Markdown (.Rmd) files covering a range of tasks and workflows in RNA-seq, single-cell RNA-seq, and related computational biology and data analysis.

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
I have a gene expression vector 'x'.
I want to calculate the mean and median of this vector.

completion:
To calculate the mean and median, use `mean()` and `median()`.

```{r,eval=FALSE}
mean(x)
median(x)
```

--- TASK END

The tasks vary in size and complexity. Some address a single operation, while others combine several analysis steps into a larger workflow.

## Purpose

The workflows draw on a combination of textbooks and educational materials, package and software documentation, publicly available examples, published workflows, and publicly available biological datasets.

The task prompts and explanatory/completion text were developed as part of the construction of this collection. The R code may include original code as well as code adapted from, or based on, publicly available examples, documentation, workflows, and other source materials.

The repository is intended to provide a structured collection of realistic biological data-analysis problems and corresponding R-based solutions that can potentially be used for LLM-assisted analysis, benchmarking, evaluation, or further development.

## Data, software, and third-party material

Many workflows make use of, or are based in part on, established R/Bioconductor packages, package documentation and examples, annotation resources, published datasets, published workflows, and other publicly available materials.

Examples may include resources such as:

- Bioconductor packages and datasets
- Public RNA-seq and single-cell RNA-seq datasets
- MSigDB gene sets
- Annotation databases and resources
- Published biological datasets

These resources are **not owned by this repository** and may have their own licenses, terms of use, attribution requirements, or citation requirements.

Where appropriate, the relevant packages, datasets, references, and external resources should be consulted for their original licensing and citation information.

Where a workflow incorporates or adapts material from a specific external source, the source and applicable license or attribution requirements should be retained or documented where appropriate.

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

The initial version preserves the R Markdown workflows as individual files. Further organization, documentation, metadata, and automated extraction of individual tasks may be added as the project develops.

## License

Unless otherwise stated, original code and other original material contributed to this repository are released under the MIT License. See the  [`LICENSE`](LICENSE) file for the license text.

Some workflows incorporate or adapt code, examples, datasets, documentation, or other materials from third-party sources. Such material is not necessarily covered by the MIT License and remains subject to the applicable license, copyright, attribution, and usage requirements of its original source.
