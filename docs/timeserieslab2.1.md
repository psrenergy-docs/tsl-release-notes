---
title: "Time Series Lab 2.1"
nav_order: 2
---

# Time Series Lab 2.1.6

:date: Date: 2026-09-09<br>
:link: Download:
[Windows](https://www.psr-inc.com/app/link/?t=d&f=timeserieslab-2.1.6-setup.zip)

## Fixed Bugs

* TSL-Data
  * Fixed the correction profile for cases with multiple solar plants sharing a common station
  * Fixed an error caused by positive UTC values
  * Fixed an error in the addition of turbine curves
  * Fixed a minor solar correction bug
  * Fixed custom wind results being skipped in output files
  * Minor warning message improvements
  * Additional protections and robustness
  * Trial license now allows up to 10 renewables (was 5) and custom turbine addition

* TSL-Scenarios
  * Fixed Markov and DLR behavior when renewable generation is not represented
  * Fixed DLR scenario generation for weekly resolution
  * Fixed Markov cluster-transition sampling being triggered for non-Markov mode
  * Improved the renewable validation process

## New Features

* TSL-Data
  * Added additional DLR outputs

* TSL-Scenarios
  * Updated the climate change add-in (CMIP6 download flow)

# Time Series Lab 2.1.5

📅 Date: 2025-05-15<br>
🔗 Download:
[Windows](https://www.psr-inc.com/app/link/?t=d&f=timeserieslab-2.1.5-setup.zip)

## Fixed Bugs

* TSL-Data
  * Fix errors related to special characters in plant name
  * Fixed an error related to deleting plants that have associated custom wind speed points
  * Added a validation to guarantee that the horizon matches the available historical years in the reanalysis database
  * Fixed an error related to GHI output data

* IHM
  * Fixed an error related to the SDDP path in the settings screen

# Time Series Lab 2.1.4

📅 Date: 2024-09-07<br>
🔗 Download:
[Windows](https://www.psr-inc.com/app/link/?t=d&f=timeserieslab-2.1.4-setup.zip)

## Fixed Bugs

* TSL-Data
  * Allow execution of the case examples without license

* IHM
  * Fixed an error related to the selection of CSPs in the select stations screen

## New Features

* IHM
  * Added the iFeedback module

# Time Series Lab 2.1.3

📅 Date: 2024-07-01<br>
🔗 Download:
[Windows](https://www.psr-inc.com/app/link/?t=d&f=timeserieslab-2.1.3-setup.zip)

## Fixed Bugs

* TSL-Data
  * Fixed an error related to the encoding of the case folder name

* IHM
  * Fixed an error when opening a case with a significant number of hydro plants (the interface was freezing when loading the case)
  * Changed the capacity factor informed in the TSL-Scenarios screen to % with 2 decimal plates

# Time Series Lab 2.1.2

📅 Date: 2024-05-15<br>
🔗 Download:
[Windows](https://www.psr-inc.com/app/link/?t=d&f=timeserieslab-2.1.2-setup.zip)

## Fixed Bugs

* TSL-Data
  * Fixed an error related to custom turbines with wake-effect option turned on
  * Fixed an error related to negative values of tilt angles for solar plants (now the absolute value will be considered)

* IHM
  * Fixed an error related to the option to generate historical scenarios when there's no hydro plant in the database
  * Added the renewable station information to the export to excel functionality in the TSL-Data screen

# Time Series Lab 2.1.1

📅 Date: 2024-04-02<br>
🔗 Download:
[Windows](https://www.psr-inc.com/app/link/?t=d&f=timeserieslab-2.1.1-setup.zip)

## Fixed Bugs

* TSL-Data
  * Fixed an error when running TSL with a subset of selected stations

* IHM
  * Fixed the bayesian network graphic with no correlated with hydrology estimation option
  * Fixed an error related to renewable plants with unitary scenario on SDDP that were considered by TSL
  * Adding protection to encoding problems (renewable plants with special characters)

# Time Series Lab 2.1

📅 Date: 2024-03-15<br>
🔗 Download:
[Windows](https://www.psr-inc.com/app/link/?t=d&f=timeserieslab-2.1.0-setup.zip)

Please refer to the [Time Series Lab 2.1 Release notes](http://psr-energy.com/software/timeserieslab-2.1.html) and check out the most important features
developed on this release.