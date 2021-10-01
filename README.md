# NOMIS API Example

NOMIS is a service provided by the United Kingdom Office for National Statistics (ONS) for distributing information gathered from census and other tools.

The workbooks requires an output folder to be created in the root of the project call "X_Output" this folder is not replicated to github to preserve confidentiality of data (and prevent sharing of large files).

The workbook provides an example scripts for accessing the NOMIS API:

+ nomis mortality.ipynb - Download population and mortality (by cause) for all local authorities listed in the assumptions
+ nomis mortality All causes only.ipynb - As above, but total mortality (all causes), no breakdown of mortality by cause.
+ nomis_ethnicity_UTLA.ipynb - Download ethnicity by Lower Super Output Area for list of LSOA.
+ nomis_ethnicity_ALL - Download ethnicity by LSOA for England using batches of geographies to minimise calls to the NOMIS API.
