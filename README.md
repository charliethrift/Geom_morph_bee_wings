# Phenotypic divergence in an island bee population: Applying geometric morphometrics to discriminate population-level variation in wing venation
[Madeleine M. Ostwald](https://orcid.org/0000-0002-9869-8835), [Charles N. Thrift](https://orcid.org/0000-0002-4257-6951), & [Katja C. Seltmann](https://orcid.org/0000-0001-5354-6048)

In prep

Please contact Charles Thrift for questions regarding the code or data (charliethrift@gmail.com)


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7869309.svg)](https://doi.org/10.5281/zenodo.7869309)


# Title 
Phenotypic divergence in an island bee population: Applying geometric morphometrics to discriminate population-level variation in wing venation

# Abstract
Phenotypic divergence is an important consequence of restricted gene flow in insular
populations. This divergence can be challenging to detect when it occurs through subtle shifts in
morphological traits, particularly in traits with complex geometries, like insect wing venation.
Here, we employed geometric morphometrics to assess the extent of variation in wing venation
patterns across reproductively isolated populations of the social sweat bee, _Halictus tripartitus_.
We examined wing morphology of specimens sampled from a reproductively isolated population
of _H. tripartitus_ on Santa Cruz Island (Channel Islands, Southern California). Our analysis
revealed significant differentiation in wing venation in this island population relative to
conspecific mainland populations. We additionally found that this population-level variation was
less pronounced than the species-level variation in wing venation among three sympatric
congeners native to the region, _Halictus tripartitus_, _Halictus ligatus_, and _Halictus farinosus_.
Together, these results provide evidence for subtle phenotypic divergence in an island bee
population. More broadly, these results emphasize the utility and potential of wing
morphometrics for large-scale assessment of insect population structure.

# Repository Directory
## Code: Contains code for data analysis in R
R Markdown file: In this document, we analyze variation in wing morphologies between three species of _Halictus_ and two populations of _Halictus tripartitus_ using geometric morphometrics. Necessary inputs for this script include:
(1) TPS files containing plotted landmark data for each wing photograph or "occurrence"
(2) CSV file containing all bee occurrence data, eg. all Hymenoptera from CCBER's GBIF or Symbiota page. This is used to match the TPS wing occurrence with its proper species and population information. Both of these inputs are stored in the Data section accessible below.

## Data: Contains both the CSV file and TPS file necessary for running code
(1) TPS file. This contains the plotted landmark data for every bee wing photograph, or "occurrence." This was created using the TPS software suite developed by Rohlf. Photographs of bee wings were inputted, and 9 homologous wing venation landmarks were selected. Coordinates of each landmark are stored in the TPS file.
(2) CSV file of bee occurrence data. This is sourced from the Cheadle Center for Biodiversity and Ecological Restoration. All Hymenoptera are included, and then are filtered down within the Rmd file to generate objects with only the relevant bee occurrences instead. Citaiton for this data: 
University of California Santa Barbara Invertebrate Zoology Collection. Occurrence dataset (ID: b03a3f0c-bfa5-4e02-b5d3-56ff38626302) https://ecdysis.org/content/dwca/UCSB-IZC_DwC-A.zip accessed via the Ecdysis Portal, ecdysis.org, 2023-05-01).




