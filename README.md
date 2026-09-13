# LLM-Assisted RNA Analysis

A collection of R Markdown workflows and task-oriented examples for bulk RNA-seq, single-cell RNA-seq, and related computational biology analyses, intended to support the development and evaluation of LLM-assisted scientific data analysis and visualization.

## Overview
This repository contains R Markdown (.Rmd) workflows developed and assembled during a four-month internship at Max Delbrück Center-BIMSB, covering a range of tasks in RNA-seq, single-cell RNA-seq, and related computational biology and data analysis.

The work contributed to the initial development and evaluation of an LLM-assisted analysis framework for RNA-seq and related computational biology tasks.”

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

The repository consists primarily of workflow-oriented R Markdown files, with each workflow containing multiple tasks ranging from small, focused operations to complete analysis workflows.

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
Each R Markdown workflow contains multiple task examples. A typical task consists of:

1. A task description and metadata
2. A natural-language prompt
3. An explanation or completion
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

Tasks vary in size and complexity. Some address a single operation, while others combine multiple analysis steps into a larger workflow.

## Purpose

The workflows were assembled from a combination of textbooks and educational materials, package and software documentation, publicly available examples, published workflows, and publicly available biological datasets.

The task prompts and explanatory/completion text were written by the repository author as part of the construction of this collection. The R code may include original code as well as code adapted from, or based on, publicly available examples, documentation, workflows, and other source materials.

The repository provides a structured collection of realistic biological data-analysis problems and corresponding R-based solutions for LLM-assisted analysis, benchmarking, evaluation, and related research.

## My contribution

My contribution focused on developing and evaluating components of the LLM-assisted analysis framework, with particular emphasis on analysis templates, task-oriented prompts, computational test cases, and R-based examples. This included:

- Developing and structuring analysis templates for bulk and single-cell RNA-seq workflows
- Developing task-oriented prompts for biological data-analysis tasks
- Constructing computational test cases for evaluating the analysis approach
- Preparing and adapting R-based examples for a range of biological data-analysis tasks

I was involved in the initial stage of the project and was not responsible for training the underlying language model.

## Data, software, and third-party material

Many workflows use or incorporate third-party software, datasets, annotation resources, examples, and other publicly available materials.

Examples may include:

- Bioconductor packages and datasets
- Public RNA-seq and single-cell RNA-seq datasets
- MSigDB gene sets
- Annotation databases and resources
- Published biological datasets

Third-party materials remain subject to their respective licenses, terms of use, attribution requirements, and citation requirements. Their inclusion in this repository does not imply that they are owned by, or licensed by, this repository.

Where a workflow incorporates or adapts material from a specific external source, the relevant source and applicable licensing or attribution requirements should be retained or documented where appropriate.

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

The current version preserves the R Markdown workflows as individual files. Further organization and documentation may be added as the project develops.

## License

Unless otherwise stated, original material in this repository that is owned by the repository author is released under the MIT License. See the [`LICENSE`](LICENSE) file for the license text.

Some workflows incorporate or adapt code, examples, datasets, documentation, or other materials from third-party sources. Such material is not necessarily covered by the MIT License and remains subject to the applicable license, copyright, attribution, and usage requirements of its original source.
