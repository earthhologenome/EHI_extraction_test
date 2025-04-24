# EHI DNA extraction test

This is the repository of the DNA extraction method test conducted by the EHI. In this study, we compare a commercial kit and two open-source solutions to extract DNA from faecal samples for downstream hologenomic analysis.

**Robust, open-source, and automation-friendly DNA extraction protocol for hologenomic research**
Jonas G. Laurisen, Christian Carøe, Nanna Gaun, Garazi Martin, Aoife Leonard, Raphael Eisenhofer, M Thomas P Gilbert, Ostaizka Aizpurua, Antton Alberdi, Carlotta Pietroni

## Compared methods

- **REF**: ZymoBIOMICS™ MagBead DNA/RNA commercial extraction kit.
- **DREX1**: Open-source custom extraction procedure developed for DNA and RNA extraction.
- **DREX2**: Open-source custom extraction procedure optimised for DNA extraction.

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
  
## Analysis procedures

The raw code used for data analysis is in the **Rmd** files stored in the root directory of this repository, while the bookdown-rendered webbook is available at:

[earthhologenome.github.io/EHI_extraction_test](https://earthhologenome.github.io/EHI_extraction_test)

While the webbook provides a user-friendly overview of the procedures, analyses can be directly reproduced using the Rmd documents. Note that the code chunks that require heavy computation have been tuned off using 'eval=FALSE'. To re-render the webbook, you can use the following code:


```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```