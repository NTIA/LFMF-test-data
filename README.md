# Low Frequency / Medium Frequency Propagation Model Test Data #

[![NTIA/ITS PropLib][proplib-badge]][proplib-link]
[![GitHub Release][gh-releases-badge]][gh-releases-link]
[![GitHub Issues][gh-issues-badge]][gh-issues-link]
[![DOI][doi-badge]][doi-link]

[proplib-badge]: https://img.shields.io/badge/PropLib-badge?label=%F0%9F%87%BA%F0%9F%87%B8%20NTIA%2FITS&labelColor=162E51&color=D63E04
[proplib-link]: https://ntia.github.io/propagation-library-wiki
[gh-releases-badge]: https://img.shields.io/github/v/release/NTIA/LFMF-test-data?logo=github&label=Release&labelColor=162E51&color=D63E04
[gh-releases-link]: https://github.com/NTIA/LFMF-test-data/releases
[gh-issues-badge]: https://img.shields.io/github/issues/NTIA/LFMF-test-data?logo=github&label=Issues&labelColor=162E51
[gh-issues-link]: https://github.com/NTIA/LFMF-test-data/issues
[doi-badge]: https://zenodo.org/badge/898078725.svg
[doi-link]: https://zenodo.org/badge/latestdoi/898078725

This repository contains a dataset used to test the NTIA/ITS implementations of the Low Frequency / Medium Frequency (LF/MF) Propagation Model.

The software tested using this dataset can be found using the links below.

- [NTIA/LFMF](https://github.com/NTIA/LFMF)
- [NTIA/LFMF-dotnet](https://github.com/NTIA/LFMF-dotnet)
- [NTIA/LFMF-matlab](https://github.com/NTIA/LFMF-matlab)
- [NTIA/LFMF-python](https://github.com/NTIA/LFMF-python)

## Data Disclaimer ##

This dataset is not intended for any use other than running unit tests against
the software in the repositories listed above. Data contained in this repository
should not be expected to reflect, for example, real-world radio propagation links.
In some instances, intentionally invalid data are provided to ensure that errors
are properly handled in the software under test.

## Dataset Versioning ##

The versioning of this dataset is tracked with a single-digit version number
in the format `v1`. This version number indicates the software versions for which
this test dataset is valid. For example, `v1` of this repository contains the dataset
used to test `v1.x` of the base C++ library and `v1.x.y` of the .NET, MATLAB®, and Python®
wrappers.

## Dataset Contents ##

- `LFMF_Examples.csv` contains a set of inputs and outputs used to test the operation of
  the `LFMF` function. A header row indicates the column names, and each subsequent row
  represents a single test case.

## License ##

MATLAB is a registered trademark of The MathWorks, Inc. See
[mathworks.com/trademarks](https://mathworks.com/trademarks) for a list of additional trademarks.

"Python" and the Python logos are trademarks or registered trademarks of the Python Software Foundation, used by the National Telecommunications and Information Administration with permission from the Foundation.

## Contact ##

For technical questions, contact <code@ntia.gov>.

## Disclaimer ##

Certain commercial equipment, instruments, or materials are identified in this project were used for the convenience of the developers. In no case does such identification imply recommendation or endorsement by the National Telecommunications and Information Administration, nor does it imply that the material or equipment identified is necessarily the best available for the purpose.
