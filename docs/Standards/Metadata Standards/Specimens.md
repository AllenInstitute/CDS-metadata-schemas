# Specimen Modeling and Relations

## Background

The Allen Institute aims to support FAIR, which includes the publication, sharing, dissemination, and exploration of data and datasets. This requires the interoperability of data and metadata for the data and datasets that are housed at AIBS or collaborating institutions/centers. To this end, we require that datasets submitted through AIBS include some effort at standardization before publication. Preferably, this requirement is met before submission, but submitters need to know the format the data must take and the schema that the data must adhere to prior to data submission.

This document attempts to describe an initial attempt at defining such a schema for specimens and processes that involves specimens as they relate to the data and datasets of interest to AIBS so that we can enable publication, searching, sharing, and exploration.

## Overview

This schema is designed to be sufficiently general so as to support multiple specimen types as well as multiple types of assays (in which specimens can function as participants).

## Metadata Integration

In an effort to enable integration, search and comparison of data, it is recommended that data is annotated using an ontology term. Ontology terms for metadata should use an OBO-format identifier, which is a CURIE that includes a prefix and then an ID string. If there is no appropriate term for use, then the user can request that we create a new term for them. However, it is not the case that every request will be granted as these are regulated by the ontology curators and curatorial efforts are constrained by both practical and theoretical considerations.

For example, if one was submitting data regarding interneurons, the appropriate term CURIE would be `CL:0000099` (interneuron). Note that the prefix indicates to which ontology the term belongs and the string following the prefix is a unique numerical sequence.

## General Requirements

As each assay and specimen type will have slightly different features/characteristics, the requirements for each may vary depending on specimen type or assay type.

## Specimens

A specimen is a material entity that has the specimen role, where a specimen role is simply a particular intent to use that entity in an investigation. Since specimens have no restriction in terms of specific material form (i.e., they can be anything at all so long as there is intent to use them in an investigation), specimens are typically categorized in terms of their material form. For example, here is a list of common specimen types:

| specimen type | controlled term | description | CURIE |
|---------------|-----------------|-------------|-------|
| brain | whole brain specimen | A specimen composed of a whole brain collected from a multicellular organism. | aio:whole_brain_specimen  |
| slab | brain specimen slab | A specimen composed of a brain slab. | aio:brain_specimen_slab |
| block | brain specimen block | A specimen composed of a brain block. | aio:brain_specimen_block |
| hemi-sected block | brain specimen hemi-sected block | A specimen composed of a hemi-sected block of a brain. | aio:brain_specimen_hemi-sected_block |
| section | brain specimen section | A specimen composed of a section of a brain. | aio:brain_specimen_section |
| brain section set | brain section set | A specimen composed of a brain sections. | aio:brain_section_set |
| cell | brain cell specimen | A specimen composed of a brain cell. | aio:brain_cell_specimen |

### Specimen Attributes for Specific Specimen Types

The following attributes are recommended for specific specimen types. Note that these attributes are not exhaustive and may be extended as needed.

#### MERFISH Specimens

## Assays

Since any material entity can function as a specimen (and in effect, be a specimen), it is important to track specimens according to the process in which they participate. They will all participate in an investigation, but the specific part of the investigation they participate in may also be of interest to a researcher. In most cases (in neurosciences), specimens participate in an investigation through an assay. An assay is a planned process with the objective to produce information about the material entity that is the evaluant, by physically examining it or its proxies. In this case, the material assays we call "specimens" serve as the evaluants of an assay. The result is some information (data item or data set) that is about the evaluant (specimen). The material entity may also be changed and used in another assay, but we shall ignore that for the time being.
