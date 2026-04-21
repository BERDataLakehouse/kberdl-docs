# Data Dictionary

A registry of all tenants and datasets in the KBase BER Data Lakehouse (K-BERDL).

<div class="grid cards" markdown>

-   :material-account-group:{ .lg .middle } **23 Tenants**

    ---

    Research programs and labs onboarded to K-BERDL

-   :material-database:{ .lg .middle } **63 Databases**

    ---

    Datasets available across all tenants

</div>

---

## Tenant Overview

| Tenant | Organization | Databases |
|---|---|:---:|
| [AI ALE](#ai-ale) | ANL | 1 |
| [Arkin Lab](#arkin-lab) | UC Berkeley | 1 |
| [BERVO data](#bervo-data) | LBNL | 3 |
| [BRaVE BREAD](#brave-bread) | ANL | 0 |
| [ENIGMA](#enigma) | LBNL (lead) | 2 |
| [ESE](#ese) | LBNL OPAL | 1 |
| [Global Users](#global-users) | — | 18 |
| [ideas](#ideas) | — | 1 |
| [KBase](#kbase) | LBNL (lead) | 9 |
| [KBase Knowledge Engine Science](#kbase-knowledge-engine-science) | LBNL | 10 |
| [LAMBDA](#lambda) | LBNL (Lead) | 0 |
| [Microbial Discovery Forge](#microbial-discovery-forge) | LBNL | 0 |
| [Microbial Ecosystems Lab](#microbial-ecosystems-lab) | Colorado State University | 0 |
| [National Energy Technology Laboratory](#national-energy-technology-laboratory) | NETL | 1 |
| [National Microbiome Data Collaborative](#national-microbiome-data-collaborative) | LBNL | 4 |
| [OPAL](#opal) | LBNL, ANL, ORNL, PNNL | 0 |
| [Phage Foundry](#phage-foundry) | LBNL | 7 |
| [Planet Microbe](#planet-microbe) | — | 2 |
| [Plant Microbe Interfaces](#plant-microbe-interfaces) | PMI | 0 |
| [Soil Microbiome Science](#soil-microbiome-science) | PNNL | 0 |
| [PROTECT](#protect) | UC Berkeley | 2 |
| [Reference Data](#reference-data) | — | 0 |
| [United States Geological Survey](#united-states-geological-survey) | USGS | 1 |

---

## Tenant Details

### AI ALE
**Organization:** ANL

Database for AI-driven adaptive lab evolution of ADP1. This database holds observed mutations crossed with conditions, passages, and strains where the mutations are observed. Key mutations are linked to specific phenotypes like growth with a novel DAHP biosynthesis enzyme and growth on a range of methoxylated aromatic compounds.

??? example "Databases (1)"
    - `aiale_dataset1`

---

### Arkin Lab
**Organization:** UC Berkeley &nbsp;|&nbsp; :material-web: [arkinlab.bio](https://arkinlab.bio/)

Leverages quantitative measurements, precision genetics, and model-driven experimentation to predict, control, and design biological function in the context of these webs.

??? example "Databases (1)"
    - `arkinlab_microbeatlas`

---

### BERVO data
**Organization:** LBNL &nbsp;|&nbsp; :material-web: [github.com/bioepic-data/bervo](https://github.com/bioepic-data/bervo)

BioEPIC data described using the Biological and Environmental Research Variable Ontology.

??? example "Databases (3)"
    - `bervodata_chess`
    - `bervodata_fao_soils`
    - `bervodata_hwsd2`

---

### BRaVE BREAD
**Organization:** ANL

Bioenergy crop–pathogen interactions, including sorghum anthracnose (*Colletotrichum sublineola*), to support predictive modeling of pathogenicity and biocontrol.

??? example "Databases (0)"
    No databases registered yet.

---

### ENIGMA
**Organization:** LBNL (lead) &nbsp;|&nbsp; :material-web: [enigma.lbl.gov](https://enigma.lbl.gov/)

Create predictive models of the impacts of microbial communities on critical processes within ecosystems.

??? example "Databases (2)"
    - `enigma_coral`
    - `enigma_genome_depot_enigma`

---

### ESE
**Organization:** LBNL OPAL &nbsp;|&nbsp; :material-web: [opal-doe.org](https://opal-doe.org/)

Developing a distributed platform that will help map the molecular determinants of microbial functions back to genomes, accelerating scalable predictive biodesign approaches.

??? example "Databases (1)"
    - `ese_ganymede`

---

### Global Users
Shared datasets and reference genomes accessible to all K-BERDL users.

??? example "Databases (18)"
    - `globalusers_aisynbio_test_1`
    - `globalusers_carbon_source_phenotypes`
    - `globalusers_demo_shared`
    - `globalusers_demo_test`
    - `globalusers_demo_test_1`
    - `globalusers_demo_test_2`
    - `globalusers_gapmind_pathways`
    - `globalusers_genomes_test1`
    - `globalusers_kepangenome_parquet_1`
    - `globalusers_nmdc_core_test`
    - `globalusers_nmdc_core_test2`
    - `globalusers_nmdc_core_test3`
    - `globalusers_nmdc_core_test4`
    - `globalusers_nmdc_flattened_biosamples`
    - `globalusers_ontology2`
    - `globalusers_ontology_source_2`
    - `globalusers_phenotype_ontology_1`
    - `globalusers_phenotype_parquet_1`

---

### ideas

??? example "Databases (1)"
    - `ideas_dataset1`

---

### KBase
**Organization:** LBNL (lead) &nbsp;|&nbsp; :material-web: [kbase.us](https://www.kbase.us/)

Community-driven research platform for systems biology.

??? example "Databases (9)"
    - `kbase_genomes`
    - `kbase_ke_pangenome`
    - `kbase_msd_biochemistry`
    - `kbase_ontology_source`
    - `kbase_phenotype`
    - `kbase_uniprot`
    - `kbase_uniref100`
    - `kbase_uniref50`
    - `kbase_uniref90`

---

### KBase Knowledge Engine Science
**Organization:** LBNL

Provides experimental phenotypes, protein structures, and microbial ecology data for linking genotype to function.

??? example "Databases (10)"
    - `kescience_alphafold`
    - `kescience_bacdive`
    - `kescience_fitnessbrowser`
    - `kescience_interpro`
    - `kescience_mgnify`
    - `kescience_paperblast`
    - `kescience_pdb`
    - `kescience_pubmed`
    - `kescience_test_mika`
    - `kescience_webofmicrobes`

---

### LAMBDA
**Organization:** LBNL (Lead) &nbsp;|&nbsp; :material-web: [lambda-doe.org](https://lambda-doe.org/)

By unifying structural biology data across BER-supported imaging resources, LAMBDA will transform how researchers discover, integrate, and analyze multimodal datasets. This will accelerate AI-driven insights into protein conformations, the relationship between genes and their expression, biological function and dynamics, and cells and their environment.

??? example "Databases (0)"
    No databases registered yet.

---

### Microbial Discovery Forge
**Organization:** LBNL

AI co-scientist and research observatory for K-BERDL-scale microbial discovery — powered by reusable skills, shared memory, and scalable data.

??? example "Databases (0)"
    No databases registered yet.

---

### Microbial Ecosystems Lab
**Organization:** Colorado State University &nbsp;|&nbsp; :material-web: [microbialecosystemslab.com](https://microbialecosystemslab.com/)

Use microbiome knowledge to better manage ecosystem function.

??? example "Databases (0)"
    No databases registered yet.

---

### National Energy Technology Laboratory
**Organization:** NETL &nbsp;|&nbsp; :material-web: [netl.doe.gov](https://netl.doe.gov/)

Currently contains the NETL Produced Water DNA database.

??? example "Databases (1)"
    - `netl_pw_dna`

---

### National Microbiome Data Collaborative
**Organization:** LBNL &nbsp;|&nbsp; :material-web: [microbiomedata.org](https://microbiomedata.org/)

Enabling microbiome science by connecting data, people, and ideas.

??? example "Databases (4)"
    - `nmdc_arkin`
    - `nmdc_flattened_biosamples`
    - `nmdc_func_annot_freshwater_rivers`
    - `nmdc_ncbi_biosamples`

---

### OPAL
**Organization:** LBNL, ANL, ORNL, and PNNL &nbsp;|&nbsp; :material-web: [opal-doe.org](https://opal-doe.org/)

The Orchestrated Platform for Autonomous Laboratories (OPAL) is a multi-laboratory project led by the U.S. Department of Energy (DOE) to turn biological discovery into a self-driving process. By combining AI, robotics, and automated experimentation, OPAL seeks to create a network of autonomous laboratories that can learn, adapt, and accelerate breakthroughs across biology, biotechnology, and energy science.

??? example "Databases (0)"
    No databases registered yet.

---

### Phage Foundry
**Organization:** LBNL &nbsp;|&nbsp; :material-web: [phagefoundry.org](https://phagefoundry.org/)

Interdisciplinary capability building a high-throughput platform for rapid design and development of countermeasures to combat emerging pathogens.

??? example "Databases (7)"
    - `phagefoundry_acinetobacter_genome_browser`
    - `phagefoundry_ecoliphages_genomedepot`
    - `phagefoundry_ecoliphagesgenomedepot`
    - `phagefoundry_klebsiella_genome_browser_genomedepot`
    - `phagefoundry_paeruginosa_genome_browser`
    - `phagefoundry_pviridiflava_genome_browser`
    - `phagefoundry_strain_modelling`

---

### Planet Microbe
**Organization:** — &nbsp;|&nbsp; :material-web: [planetmicrobe.org](https://www.planetmicrobe.org/)

Enabling the discovery and integration of oceanographicomics, environmental and physiochemical data layers.

??? example "Databases (2)"
    - `planetmicrobe_planetmicrobe`
    - `planetmicrobe_planetmicrobe_raw`

---

### Plant Microbe Interfaces
**Organization:** PMI &nbsp;|&nbsp; :material-web: [pmiweb.ornl.gov](https://pmiweb.ornl.gov/)

Focuses on revealing the genomic bases underpinning the selection of symbiotic plant-microbe partnerships, assessing how the physical and chemical environment structures the host plant's microbiome, and determining how microbial community composition and host genetics combine to respond to environmental challenges.

??? example "Databases (0)"
    No databases registered yet.

---

### Soil Microbiome Science
**Organization:** PNNL &nbsp;|&nbsp; :material-web: [pnnl.gov/projects/soil-microbiome](https://www.pnnl.gov/projects/soil-microbiome)

Advancing our understanding of how soil microbial communities respond to—and affect—changing environmental conditions.

??? example "Databases (0)"
    No databases registered yet.

---

### PROTECT
**Organization:** UC Berkeley

Pro/Prebiotic Regulation for Optimized Treatment and Eradication of Clinical Threats (PROTECT) is pioneering microbiome engineering to design probiotic communities that prevent lung infections by pathogens.

??? example "Databases (2)"
    - `protect_genomedepot`
    - `protect_integration`

---

### Reference Data
Collection of reference data that are available to all users and regularly updated by the KBase team.

??? example "Databases (0)"
    No databases registered yet.

---

### United States Geological Survey
**Organization:** USGS &nbsp;|&nbsp; :material-web: [usgs.gov](https://www.usgs.gov/)

Sharing produced water and river geochemistry data for cross-tenant analysis.

??? example "Databases (1)"
    - `usgs_produced_waters`
