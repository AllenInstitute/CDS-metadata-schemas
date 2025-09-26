# Process Types for Taxonomy Tools

Within AIBS, cell type taxonomy creation occurs iteratively and across several teams and workflows. As part of development of BKP Taxonomy Tools, we need to develop a simple model of the taxonomy creation process so that we can support creation, tracking and finding essential metadata describing taxonomies in the BKP Registry.

This document describes two key process types involved in taxonomy creation: Clustering Process and Taxonomy Creation Process. Each process type includes a description, input and output data types, and relevant metadata fields.

## Clustering Process

Clustering is the process of organizing and classifying observations into groups or clusters based on similarities or patterns.

For taxonomy development, the clustering process involves grouping similar cell types based on their gene expression profiles. This is typically done using algorithms such as k-means, hierarchical clustering, or graph-based methods. The goal is to identify distinct clusters that represent different cell types or states.

Clustering processes use oberservational matrices as input and produce cluster sets as output.

| Field Name        | Description                                                  | input               | output              |
|-------------------|--------------------------------------------------------------|---------------------|---------------------|
| clustering process      | The process of organizing and classifying observations into groups or clusters based on similarities or patterns.                           | observation matrix          | cluster set         |

## Taxonomy Creation Process

Cell type taxonomy creation process is the process of organizing cells or clusters into a systematic classification of cell types and their heirarchical relationships and groupings.

For taxonomy development, this involves defining cell types based on their characteristics, such as gene expression profiles, morphology, and functional properties. The taxonomy creation process may involve expert curation and validation to ensure the accuracy and relevance of the classification.

| Field Name        | Description                                                  | input               | output              |
|-------------------|--------------------------------------------------------------|---------------------|---------------------|
| taxonomy creation process      | The process of organizing cells or clusters into a systematic classification of cell types and their heirarchical relationships and groupings.                           | cluster set          | cell type taxonomy |

### Other Relevant Metadata Fields

| Field Name        | Description                                                  |
|-------------------|--------------------------------------------------------------|
| algorithm         | The specific algorithm or method used for clustering or taxonomy creation (e.g., k-means, hierarchical clustering, graph-based methods). |
| authors           | The individuals or teams responsible for conducting the clustering or taxonomy creation process. |
| modality/technique | The specific modality or technique used to generate the data for clustering or taxonomy creation (e.g., single-cell RNA sequencing, spatial transcriptomics). Refer to [Experimental Techniques CV](https://github.com/AllenInstitute/CDS-metadata-schemas/blob/2527ffc09fa8eb67140ae1704da0b7d6479e2dbe/docs/Controlled%20Vocabularies/Experimental%20Techniques.md) for values. |
| species          | The species from which the data was derived (e.g., human, mouse). Refer to [species CV](https://github.com/AllenInstitute/CDS-metadata-schemas/blob/2527ffc09fa8eb67140ae1704da0b7d6479e2dbe/docs/Controlled%20Vocabularies/Species%20CV.md) for values. |
| annotations       | Any additional annotations or labels associated with the clusters or cell types (e.g., known markers, functional properties), from a shared annotation sheet. |

## Changelog

- 2025-09-02: Initial creation of the document.
- 2025-09-02: Added detailed descriptions and examples for clustering and taxonomy creation processes.
- 2025-09-02: Updated terminology to align with latest standards in taxonomy development.
- 2025-09-02: Added relevant metadata fields for both process types.
