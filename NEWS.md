---
title: "News"
---

# lifecontingencies 1.3.10

* Added a `NEWS.md` file to track changes to the package.
* Fix class calls
* moved to bibentry and fix missing links

# Version 1.3.8

* Fixed issues in biblio
* Removed vignette intro due to latex incompatibility

# Version 1.3.7

* Mortality projections with StMoMo added
* Added a new vignette on Pension evaluation by Ivan Williams
* Added DOI

# Version 1.3.5

* add vectorization of pxt(), qxt(), axn(), Axn()
* start vectorization of axyzn() (devel version)
* Started moving docs in Roxygen

# Version 1.3.4
* Fixed issue in Macaulay duration
* Recreated old data in data-raw

# Version 1.3.3

* Added geometric discounting clarifications

# Version 1.3.2

* changes in Pension Funding Vignette

# Version 1.3.1

* removed .sty files as CRAN request
* added unit test on mdt functions
* start deprecating pxyt, qxyt, exyt

# Version 1.3

* Added qxt.fromQxprime to get decrement from ASDT decrements
* Updated vignette on pension funding

# Version 1.2.5

* New vignette on pension funding
* add associated single decrement table section
* added function to compute associated single decrement rate from multiple decrement table
* Various fixing

# Version 1.2.2

* Added registration of Dynamic libraries
* Revision of vignettes

# Version 1.2.1

* Small fixes

# Version 1.2

* Added initialize method for actuarialtable and lifetable classes

# Version 1.1.14

* Fixed small issue on remove NA for data.frame
* Fixed medium bugs affecting Axyn and Ax (see github issues #1 and #2)

# Version 1.1.12

* Cosmethic amendments

# Version 1.1.10

* Fixed AExn=1 when n=0
* Fixed pxt with multiple decrements when t=0
* Small changes to vignettes

# Version 1.1.6

* Add GitHub repository.
* first usage of Rcpp (hidden code). 
* New vignette for a quick introduction to the package. 

# Version 1.1.5

* Numerical tests vignette replaced with Unit Root testing.
* Replaced incoherencies within the manual on lifetable and actuarialtable method.
* Added rmdt to sample from multiple contingencies object
* Fixed description and namespace

# Version 1.1

* Multiple decrements officially introduced in the package (various methods added, as well as a vignette)
* An introductory vignette for multiple decrements

# Version 1.0.6

* Changed vignettes removing parallel function to cope with CRAN policies
* Added SoA illustrative service table in data
* Introduced multiple decrements by the mdt class

# Version 1.0.5

* Fix an issue with fractional probabilities (Kevin J. Owens)
* Fix an issue with multiple lives random generation functions (Kevin J. Owens).
* Improved mortality vignettes
* life tables can now be exported as markovchainList objects

# Version 1.0

*  Fix an issue with print method on actuarialtable
*  Added reference to JSS Published Paper
*  Deeply improved mortality vignette (thanks to Gian Paolo Clemente, co-author)

# Version 0.9.8.6

* Add annuities paid in advance / deferred option
* Add functions getLifecontingencyPV and getLifecontingencyXyzPV to obtain Present Value given the age of death.

# Version 0.9.8.5

* Fixed axn function.
* Finalized main vignette.

# Version 0.9.8
* Improved documentation.
* Add as.numeric method for lifetable and actuarialtable objects.
* Add power argument to APV function to evaluate higher moments.

# Version 0.9.7

* Minor changes to documentation

# Version 0.9.6

* Add summary method for lifetable and actuarialtable objects
* Improvements and fix in simulation of life contingent insurances
* Add rLifeContingenciesXyz function
* Improvements in the vignette

# Version 0.9.5

* ALM section to main vignette was added.
* rLife has been improved.
* Functions to switch from interest to discount and vice - versa have been added.
* Multiple life insurances function now work properly.
* Add function to generate variate from two life contingencies.
* Add French and UK life ta

# Version 0.9.3

* Revision to lifecontingencies vignettes to cope with Journal of Statistical Software style.
* Minor changes and bug fixes

# Version 0.9.2

* rLifeContingencies has been parallelized
* updated demoIta dataset
* added n-year term insurance function AExn
* final revision of package vignettes

# Version 0.9.1

* conventions on parameters made uniform.
* minor changes in the vignettes and functions documentation. 

# Version 0.9

* adding rLifeContingencies function, to simulate random variates from life contingencies distribution.
* deep revision of vignettes.
* various bug fixed.

# Version 0.1.1

* Minor fixes
* Set R required version to 2.14

# Version 0.1

* Deep revision of vignettes
* Add increasing annuity function, Iaxn
* Minor fixes

# Version 0.0.7

* Added rLife function to simulate random times until deaths
* Improved financial mathematics functions
* Improved documentation and vignettes

# Version 0.0.6

* Improved documentation
* Improved financial functions
* Added function to obtain lifetables from raw survival or deaths probabilites

# Version 0.0.5

* Added methods for lifecontingencies objects
* improved vignettes (added JSS template).

# Version 0.0.4

* Improved documentation
* Added demographic functions
* Added US Social Security life tables.

# Version 0.0.3

* Improved documentation
* Add some multiple life functions
* fix a bug in method getOmega

# Version 0.0.2

* Specific interest rate can be given directly to the actuarial life contingencies functions that override lifetable one
* Update Axn for fractional ages
* pxn function now allows non integer x
* correct coerce methods to data.frame
* Some minor changes in the documentation

# Version 0.0.1

* First version of life contingencies
