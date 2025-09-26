# Species Controlled Vocabulary

The debate over what a species is has been ongoing for centuries, with various definitions proposed by different scientists and philosophers. However, for the purposes of this controlled vocabulary, we will use a practical definition that aligns with the needs of biological and biomedical research. A species is defined as a group of organisms that can interbreed and produce fertile offspring under natural conditions. This definition, known as the Biological Species Concept, is widely accepted in the scientific community and provides a clear criterion for distinguishing between different species.

Species are a critical component of biological and biomedical research, as they provide the foundational context for understanding the biology, behavior, and ecology of various organisms. Accurate identification and classification of species are essential for effective communication, data sharing, and collaboration within the scientific community. This controlled vocabulary aims to standardize the representation of species used in our data systems, ensuring consistency and clarity across different datasets and studies.

This controlled vocabulary lists the species that are currently supported in our data systems. Each species is identified by its NCBI Taxonomy ID, which is a unique identifier assigned by the National Center for Biotechnology Information (NCBI) to each species in their taxonomy database. The NCBI Taxonomy ID is widely used in biological and biomedical research to ensure consistent and accurate identification of species across different databases and studies.

| ID                  | Binomial Name                     | Common Name                  |
|---------------------|---------------------------|--------------------------|
| NCBITaxon:9606      | Homo sapiens              | human                    |
| NCBITaxon:9483      | Callithrix jacchus        | common marmoset          |
| NCBITaxon:10090     | Mus musculus              | mouse                    |
| NCBITaxon:9544      | Macaca mulatta            | rhesus macaque           |
| NCBITaxon:60711     | Chlorocebus sabaeus       | green monkey             |
| NCBITaxon:9999      | Urocitellus parryii       | Arctic ground squirrel   |
| NCBITaxon:9361      | Dasypus novemcinctus      | nine-banded armadillo    |
| NCBITaxon:9598      | Pan troglodytes           | chimpanzee               |
| NCBITaxon:9669      | Mustela putorius furo     | ferret                   |
| NCBITaxon:9593      | Gorilla gorilla           | western gorilla          |
| NCBITaxon:9545      | Macaca nemestrina         | pig-tailed macaque       |
| NCBITaxon:13616     | Monodelphis domestica     | gray short-tailed opossum|
| NCBITaxon:9986      | Oryctolagus cuniculus     | rabbit                   |
| NCBITaxon:10116     | Rattus norvegicus         | rat                      |
| NCBITaxon:9541      | Macaca fascicularis       | crab-eating macaque      |
| NCBITaxon:9534      | Chlorocebus aethiops      | grivet                   |
| NCBITaxon:9614      | Canis latrans             | coyote                   |
| NCBITaxon:9555      | Papio anubis              | olive baboon             |
| NCBITaxon:27679     | Saimiri boliviensis       | black-capped squirrel monkey |
| NCBITaxon:9521      | Saimiri sciureus          | squirrel monkey          |
| NCBITaxon:30608     | Microcebus murinus        | mouse lemur              |
| NCBITaxon:37293     | Aotus nancymaae           | owl monkey               |
| NCBITaxon:37347     | Tupaia belangeri          | treeshrew                |
| NCBITaxon:10181     | Heterocephalus glaber     | naked mole rat           |
| NCBITaxon:9823      | Sus scrofa                | pig                      |
| NCBITaxon:9539      | Macaca*                   | macaque*                 |

## Usage Notes

For animals simply named 'macaque', we use the taxon 'Macaca' which is actually a genus (not a species). Since these animals are grouped together for analysis purposes, we will use the genus term (NCBITaxon:9539).

## Changelog

- **September 26, 2025 -- Version 1.0.1**
  - Updated documentation

- **August 28, 2025 -- Version 1.0.1**
  - Changed column from 'label' to 'binomial name'
  - Changed column from 'synonyms' to 'common name'
  - Added NCBITaxon:9539 (Macaca)
  - Updated Usage Notes to describe how to handle generic 'macaque'

- **August 7, 2025 — Version 1.0.0**
  - Initial release of the Species Controlled Vocabulary.
  - Added 25 species entries with NCBI Taxon IDs, labels, and synonyms.
  