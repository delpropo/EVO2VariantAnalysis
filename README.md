# Project Document: Using EVO2 for Predicting Impacts of Non-Coding Regions Variants

## Purpose
The purpose of this project is to utilize EVO2, a DNA foundation model developed by the Arc Institute, to predict the impacts of certain genetic variants, with a specific focus on non-coding regions and their influence on protein expression and phenotype related to Ataxia. The goal is to determine whether any of the numerous variants in non-coding regions could contribute to Ataxia phenotypes.


## Scope

This project will focus on:

- Exploring the capabilities of EVO2 in analyzing non-coding genetic variants and their potential influence on Ataxia phenotypes.
- Developing a workflow to process variant data and predict potential impacts using EVO2.
- Utilizing and adapting existing test data, derived from the Snakemake Workflows for DNA sequencing (https://github.com/snakemake-workflows/dna-seq-varlociraptor) and vembrane output files (https://github.com/vembrane/vembrane), to facilitate this analysis.


## Objectives
- Gain familiarity with the EVO2 model and its applications.
- Develop a processing pipeline that can accept TSV files with variant data.
- Evaluate the impact of specific variants on protein expression, focusing on non-coding regions.

## Deliverables
- A fully functional pipeline that accepts TSV files of variants, processes them, runs them through the EVO2 model, and outputs results.
- A report detailing the methods used, challenges faced, and results obtained.
- Documentation for future users to replicate or expand the analysis.

## Timeline
- Project initiation and background research: TBD
- Initial setup and exploration of EVO2: TBD
- Workflow development and testing: TBD
- Analysis and reporting: TBD
- Final presentation: TBD

## Methodology
- Utilize Python and an appropriate workflow management tool compatible with Slurm.
- Use test datasets from the `WES_Analysis_11340_9740` repository as initial input.
- Implement and refine a pipeline for processing and analyzing variants using EVO2.

## Resources
- EVO2 model details from Arc Institute: [Arc Institute EVO2](https://github.com/ArcInstitute/evo2)
- Test data: [WES Analysis Repository](https://github.com/delpropo/WES_Analysis_11340_9740/tree/main/tests/data)
- Workflow management tools: TBD (consider exploring alternatives to Cookiecutter Data Science for Python and Slurm compatibility)

## Evaluation Criteria
- Accuracy and reliability of the workflow and predictions.
- Clarity and completeness of documentation and reporting.
- Innovation in workflow design and problem-solving approaches.

## Background Information
EVO2 is a genome modeling and design framework capable of analyzing DNA sequences across various domains of life, particularly valuable in studying non-coding regions.

## Support and Guidance
- Regular check-ins and feedback sessions: TBD
- Access to shared resources and guidance from [Your Name]: TBD

## Challenges and Constraints
- The need to adapt to a currently unfamiliar model (EVO2).
- Ensuring compatibility with cluster resources and data formats.

## Communication
- Preferred channel for communication: TBD
- Frequency of updates and meetings: TBD

## Risk Management
- Identify potential technical obstacles early and seek guidance as needed.
- Regularly back up work and maintain version control.

