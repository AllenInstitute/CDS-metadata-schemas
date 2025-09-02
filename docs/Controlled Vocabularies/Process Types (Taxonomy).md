# Process Types for Taxonomy Tools

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

## Changelog

- 2025-09-02: Initial creation of the document.
- 2025-09-02: Added detailed descriptions and examples for clustering and taxonomy creation processes.
- 2025-09-02: Updated terminology to align with latest standards in taxonomy development.
