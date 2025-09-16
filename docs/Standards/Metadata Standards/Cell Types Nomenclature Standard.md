# Cell Types Consensus Nomenclature Standard

## Overview

This document outlines the standard nomenclature for consensus cell types used in our datasets. Consistent naming conventions are crucial for effective data sharing, analysis, and interpretation across various research projects.

## Nomenclature Guidelines

1. **General Structure**: Cell type names should follow the format: `[Location] [PatchSeq] [Literature] [Transcriptomics] [Neurotransmitter]`. For example, `STR FS PTHLH ST18 GABA`.
2. **Location**: Use standardized anatomical terms from the Allen Brain Atlas. Abbreviations are controlled and should be consistent (refer to this [Anatomy List](https://alleninstitute.github.io/abc_atlas_access/_downloads/d86c2fd08499526ee8055d3d226b284a/abbreviation_list.html) for guidance).
3. **Patch Seq**: Use standardized terms for patch-seq classifications (e.g., FS for Fast Spiking). See this [Patch-Seq List] for reference. [*optional*]
4. **Literature**: This slot is for historical names (i.e., names that have been used in prior publications or names that have been used historically for this type of cell). [*optional*]
5. **Transcriptomics**: This slot is for gene expression-based classifications (e.g., PVALB). This slot can accomodate two gene names -- the first for broad gene and the second for fine gene. (e.g., NMU-TAC3) See this [Gene List](https://alleninstitute.github.io/abc_atlas_access/_downloads/d86c2fd08499526ee8055d3d226b284a/abbreviation_list.html) for reference.
6. **Neurotransmitter**: Specify the primary neurotransmitter (e.g., GABA, Glutamate, Dopamine). See this [Neurotransmitter List](https://alleninstitute.github.io/abc_atlas_access/_downloads/d86c2fd08499526ee8055d3d226b284a/abbreviation_list.html) for reference.

### Additional Guidelines

7. **Capitalization**: Please conform to the CV lists provided for each slot to ensure consistency in capitalization.
8. **Abbreviations**: Use standardized abbreviations for all terms in names. Avoid ambiguous abbreviations. Refer to this [Abbreviation List](https://alleninstitute.github.io/abc_atlas_access/_downloads/d86c2fd08499526ee8055d3d226b284a/abbreviation_list.html) for guidance.
9. **Special Characters**: Do not use special characters (e.g., &, %, $, #) in cell type names. Use space to separate terms.
10. **Documentation**: Maintain a comprehensive list of all cell types you name, along with their definitions and any relevant references.
11. **Review Process**: Regularly review and update the nomenclature to incorporate new discoveries and consensus in the scientific community.

## Implementation

- All datasets must adhere to this nomenclature standard.
- Data submission templates should include fields for cell type names following the specified format.
- Training sessions will be conducted to familiarize researchers with the nomenclature guidelines.

## Changelog

### September 6, 2025 Version 0.0.1

- Initial draft of the Cell Types Consensus Nomenclature Standard.
- Defined the general structure and guidelines for naming cell types.
