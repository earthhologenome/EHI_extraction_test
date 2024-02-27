# EHI DNA extraction test

This is the repository of the DNA extraction method test conducted by the EHI. In this study, we compare a commercial kit and two open-source solutions to extract DNA from faecal samples for downstream hologenomic analysis.

## Compared methods

- **ZYMO**: ZymoBIOMICS™ MagBead DNA/RNA commercial extraction kit.
- **DREX**: Open-source custom extraction procedure developed for DNA and RNA extraction.
- **EHEX**: Open-source custom extraction procedure optimised for DNA extraction.

## Tested species

The performance of the extraction methods is tested using 24 samples belonging to 12 vertebrate species:

- **Amphibians**
  - *Calotriton asper*
  - *Lissotriton helveticus*
  - *Salamandra atra*
- **Birds**
  - *Geospizopsis unicolor*
  - *Perisoreus infaustus*
  - *Zonotrichia capensis*
- **Mammals**
  - *Plecotus auritus*
  - *Sciurus carolinensis*
  - *Trichosurus vulpecula*
- **Reptiles**
  - *Chalcides striatus*
  - *Natrix astreptophora*
  - *Podarcis muralis*
  
## Analysis code

The data analysis code is presented in two RMarkDown documents.

- **[EHI_extraction_test.Rmd](EHI_extraction_test.Rmd)**: this is the main code in which all primary statistical analyses are carried out.
- **[community_analysis.Rmd](community_analysis.Rmd)**: this is the auxiliary code that conducts microbial community-level analyses.