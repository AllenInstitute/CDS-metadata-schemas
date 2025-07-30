# Community Data Standards Metadata Schemas and Documentation

This is the repository for metadata schemas as used by the Community Data Standards Team (CDS). This repository contains files, documents, and code essential for CDS metadata curation.

## Table of Contents

- [Community Data Standards Metadata Schemas and Documentation](#community-data-standards-metadata-schemas-and-documentation)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
    - [Why Use This Repository?](#why-use-this-repository)
    - [Using This Repository](#using-this-repository)
    - [Browse Metadata Schemas](#browse-metadata-schemas)
    - [Review Documentation](#review-documentation)
    - [Propose New Terms or Schemas](#propose-new-terms-or-schemas)
    - [How to Contribute](#how-to-contribute)
    - [Terminology](#terminology)
  - [Status Board](#status-board)

## Overview

This repository is maintained by the Community Data Standards (CDS) team to support the development, documentation, and use of metadata schemas and standards across Allen Institute engineering teams and partner applications. It serves as a centralized resource for:
  
- Defining and maintaining metadata schemas used in internal services, external applications, and public data releases.
  
- Documenting standards and best practices for metadata modeling, validation, and versioning. This includes documenting what standards are desirable to align with for different topical areas.
  
- Managing controlled vocabularies (CVs) and enabling community input through a transparent term request and review process.
  
- Facilitating collaboration by providing clear contribution pathways for engineers, data curators, and scientific stakeholders.

The repository includes artifacts that support schema development such as data dictionaries or abstract data models, schema definitions (e.g., LinkML, JSON Schema), supporting documentation, review workflows, and tools for validating and integrating metadata. It is intended for use by CDS members, Allen Institute for Brain Science software and data engineering teams, and (eventually) external collaborators who work with structured metadata related to neuroscience data products.

### Why Use This Repository?

This repository is a central reference point for engineers working on applications, services, and pipelines that produce, consume or integrate metadata. Engineers should consult this repository when they:
  
- Integrate with Internal or External Systems:  Ensure their service or application uses the metadata schemas appropriately when interfacing with shared APIs, data platforms, or release pipelines.  

  - Understand why metadata are structured a certain way and how individual fields are intended to be used, both from a scientific/semantic perspective and from an engineering perspective.

  - Avoid misusing fields – for example by overloading a field with additional meaning beyond its intended purpose, which can compromise metadata integrity.
  
- Validate, generate, or integrate metadata

  - Use schema definitions to validate metadata before submitting or deploying.

  - Generate metadata in the correct format for ingestion into services, apps, or archives.

  - Understand how schemas map to internal applications and external resources.
  
- Update or extend metadata models

  - Propose changes to existing schemas when requirements evolve.

  - Contribute to new schemas for internal tools, new datasets or service-specific workflows.
  
- Align with standards and best practices.

  - Follow naming conventions, standard data types and modeling principles.

  - Reuse existing controlled vocabularies and schema components.

  - Take advantage of semantic enhancements (e.g., synonyms, ontology mappings, linked references) embedded in vocabularies for inclusion in apps or tools.
  
- Understand the Metadata Lifecycle

  - Learn how metadata is reviewed, approved, versioned and released.

  - Understand schema ownership, responsibilities, and change management.

### Using This Repository

This repository is organized to support easy access to metadata schemas, documentation, and contribution workflows.  

### Browse Metadata Schemas

All schemas are located in teh `schemas/` directory. Each schema is a structured file (YAML, JSON, LinkML) is accompanied by a README document that contains descriptive information about that schema including an explanation of its fields, intended use, and version.

The Status Board shows the current version and reivew status of each schema.

### Review Documentation

The `docs/` directory contains:

- Best practices for metadata schema development.
- Schema versioning and naming conventions.
- Review and approval workflows (see the [CDS review and approval workflow](https://alleninstitute.atlassian.net/wiki/x/E4DNJw)).
- Best practices for using controlled vocabularies.

### Propose New Terms or Schemas

Use GitHub issues to:

- Propose new controlled vocabulary terms.
- Suggest changes to existing schemas.
- Submit new schemas for review.

Follow the instructions in the [How to Contribute](https://github.com/AllenInstitute/CDS-metadata-schemas/blob/300725patch1/README.md#L71) file for how to create issues and pull requests.

### How to Contribute

The CDS team supports community input and collaboration in developing, maintaining, and updating metadata schemas and documents.

- To propose new controlled vocabulary terms, use the [Controlled Vocabulary Term Request](https://github.com/AllenInstitute/CDS-metadata-schemas/issues) template.

- To suggest changes to an existing schema, use the [New Metadata Element](https://github.com/AllenInstitute/CDS-metadata-schemas/issues) template.

- To submit a new schema for review, use the [New Schema Request](https://github.com/AllenInstitute/CDS-metadata-schemas/issues) template.

- For any other issues or questions, please create a new issue in the [CDS-metadata-schemas issue tracker](https://github.com/AllenInstitute/CDS-metadata-schemas/issues/new) or email [data.curation@alleninstitute.org](data.curation@alleninstitute.org).

### Terminology

**Metadata** is the human and machine-readable descriptive information about a data resource that is necessary for tracking and using the data it describes. In the context of CDS, metadata is descriptive information that is necessary for understanding data at the Allen Institute for Brain Science. This information is provided in a structure defined by the schema.

A **schema** is a human and machine-readable file-based specification for metadata. A specification defines the metadata structure and fields, including field name, description, format, and cardinality.

An **owner** of a schema is the person or group of persons that assume responsibility for its creation, documentation, and movement through the metadata approval process.

**Contributors** are any members of CDS, Allen Institute for Brain Science or scientific community who suggest, contribute, or review updates to the metadata schemas.

**Submitters** are any members of CDS, Allen Institute for Brain Science or scientific community who submit data or metadata.

**Committers** are any members of CDS team or the Allen Institute for Brain Science with commit privileges to the CDS-metadata-schemas GitHub repo.

A metadata schema has the status of **submitted** if and only if it has been uploaded as an attachment to an issue ticket on the CDS-metadata-schemas issue tracker.

A metadata schema has the status of **under CDS review** if and only if it has the status of submitted and the CDS team has acknowledged its receipt and has assigned reviewers to the schema.

A metadata schema has the status of **under revision by owner** if and only if it has the status of under CDS review and the owner has received recommended changes from reviewers.

A metadata schema has the status of **accepted by CDS** if and only if it has been under CDS review and CDS has deemed there are no outstanding necessary changes to the schema.

A metadata schema has the status of **endorsed CDS standard** if and only if it has been accepted by CDS team, and successfully completed the CDS data standards process.

## Status Board

Here are the CDS metadata schemas and their statuses.

| Schema | Version | Release | Status |
|:--|:--|:--|:--|
| [Some Metadata Schema] | [version] |  [2025-06-27] | none |
| | | | |