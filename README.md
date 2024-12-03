# NTIA/ITS Propagation Library Test Data Template Project #
<!-- TODO-TEMPLATE: Update software name above to "ModelName Test Data" -->
<!-- TODO-TEMPLATE: README BADGES

- The first badge links to the PropLib Wiki and does not need to be edited
- The second badge automatically displays and links to the most recent GitHub Release.
    - Make sure to update the [gh-releases-badge] and [gh-releases-link] URLs with your repo name
- The third badge displays open GitHub Issues
    - Update the repository name in [gh-issues-badge]
    - Update the repository name in [gh-issues-link]
- The fourth badge displays and links the Zenodo DOI
    - Get your repository ID from https://api.github.com/repos/NTIA/{repo}
    - Populate the repository ID in [doi-link] and [doi-badge]
-->
[![NTIA/ITS PropLib][proplib-badge]][proplib-link]
<!-- TODO-TEMPLATE: Add badges. See above for details.
[![GitHub Release][gh-releases-badge]][gh-releases-link]
[![GitHub Issues][gh-issues-badge]][gh-issues-link]
[![DOI][doi-badge]][doi-link]
-->
[proplib-badge]: https://img.shields.io/badge/PropLib-badge?label=%F0%9F%87%BA%F0%9F%87%B8%20NTIA%2FITS&labelColor=162E51&color=D63E04
[proplib-link]: https://ntia.github.io/propagation-library-wiki
[gh-releases-badge]: https://img.shields.io/github/v/release/NTIA/TODO-TEMPLATE?logo=github&label=Release&labelColor=162E51&color=D63E04
[gh-releases-link]: https://github.com/NTIA/TODO-TEMPLATE/releases
[gh-issues-badge]: https://img.shields.io/github/issues/NTIA/TODO-TEMPLATE?logo=github&label=Issues&labelColor=162E51
[gh-issues-link]: https://github.com/NTIA/TODO-TEMPLATE/issues
[doi-badge]: https://zenodo.org/badge/TODO-TEMPLATE.svg
[doi-link]: https://zenodo.org/badge/latestdoi/TODO-TEMPLATE

<!-- TODO-TEMPLATE: Replace the below description with one for your software -->
This code repository is a template repository for test data repositories in the NTIA/ITS
Propagation Library (PropLib). This template is intended for developers wishing
to provide common test data to multiple implementations of the same PropLib software.
Instructions on how to use this repository are found in
[the PropLib Template Wiki](https://github.com/NTIA/proplib-template/wiki).

Additional template repositories exist for building C++ PropLib libraries and
.NET, MATLAB, and Python wrappers for those libraries. See:

- [NTIA/proplib-template](https://github.com/NTIA/proplib-template)
- [NTIA/proplib-template-dotnet](https://github.com/NTIA/proplib-template-dotnet)
- [NTIA/proplib-template-matlab](https://github.com/NTIA/proplib-template-matlab)
- [NTIA/proplib-template-python](https://github.com/NTIA/proplib-template-python)

## Contact ##

For questions about using this template repository, contact <aromaniello@ntia.gov>

<!-- TODO-TEMPLATE: Create the README contents. Boilerplate provided below.

The software tested using this dataset can be found using the links below.

- [NTIA/TODO-TEMPLATE](https://github.com/NTIA/TODO-TEMPLATE)
- [NTIA/TODO-TEMPLATE-dotnet](https://github.com/NTIA/TODO-TEMPLATE-dotnet)
- [NTIA/TODO-TEMPLATE-matlab](https://github.com/NTIA/TODO-TEMPLATE-matlab)
- [NTIA/TODO-TEMPLATE-python](https://github.com/NTIA/TODO-TEMPLATE-python)

## Disclaimer ##

This dataset is not intended for any usage other than running unit tests against
the software in the repositories listed above. Data contained in this repository
should not be expected to reflect, for example, real-world radio propagation links.
In some instances, intentionally invalid data are provided to ensure that errors
are properly handled in the software under test.

## Data Versioning ##

The version of this dataset is tracked with a simple, single-digit version number
in the format `v1`. This version number indicates the software versions for which
this test dataset is valid. For example, `v1` of this repository contains the dataset
used to test `v1.x` of the base C++ library, and `v1.x.y` of the .NET, MATLAB, and Python
wrappers.

## Dataset Contents ##

TODO-TEMPLATE: Document each included data file or group of data files. Example provided
below.

- `AeronauticalStatisticalModelTestData.csv` contains sets of inputs and outputs used
  to test the operation of the `AeronauticalStatisticalModel` function. A header row
  indicates the column names, and each subsequent row represents a single test case.
- `CombinedProfiles.csv` contains a set of terrain profiles in the PFL format, used to
  test the point to point mode operation. Each row should be read as a single array.

## Contact ##

For technical questions, contact <code@ntia.gov>.

-->
