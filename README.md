[![License](https://img.shields.io/badge/license-GPL%20%28%3E=%203%29-lightgrey.svg?style=flat)](http://www.gnu.org/licenses/gpl-3.0.html)
[![Lifecycle:
manturing](https://img.shields.io/badge/lifecycle-manturing-blue.svg)](https://www.tidyverse.org/lifecycle/#manturing)

# MSDM
Overprediction correction approaches in species distribution models


## Installation

```r
require(devtools)  
install_github("sjevelazco/MSDM")  
require(MSDM)
```


## Description

MSDM provides tools to correct overprediction of species distribution models. There is two main functions `MSDM_Priori()` and `MSDM_Posteriori()`. 

*.* **`MSDM_Priori`**: offers four methods, named *XY*, *MIN*,  *CML*, and *KER*. These creates spatial predictor variables which have to be used with environmental variable to construct species distribution models. These approaches constrain the suitability predicted by SDMs to species occurrences.

*.* **`MSDM_Posteriori`**: provides four methods, named *OBR*, *PRES*, *LQ*, *MCP*, and *BMCP*. All theme correct overprediction of species distribution models based on occurrences and suitability patterns of species. 

### CITATION:
**Medes, P.; Velazco S.J.E.; Andrade A.; De Marco, P. Dealing with overprediction in species distribution models: how adding distance constraints can improve model accuracy, Ecological Modelling, in press.**

> Test the package and give us feedback [here](https://github.com/andrefaa/MSDM/issues) or send an e-mail to sjevelazco@gmail.com or andrefaandrade@gmail.com!

> MSDM package is integrated to [ENMTML](https://github.com/andrefaa/ENMTML) R package
