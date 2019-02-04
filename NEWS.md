# swissknife 0.9

* Add R/valueToColor.R

# swissknife 0.8

* plotBitScatter(x, y = NULL) now also works for x being a two-column matrix

# swissknife 0.7

* add functions to calculate and plot phasograms, e.g. to measure nucleosome
  repeat length in MNase data (R/phasograms.R, src/phasograms.cpp)

# swissknife 0.6

* added tests for sampleControlElements() to cover all code (coverage gaps detected
  with covr::zero_coverage(covr::package_coverage()))

# swissknife 0.5

* sampleControlElements() now catches cases with too few control elements to match the target distribution

# swissknife 0.4

* sampleControlElements(x = list(), ...) now works correctly

# swissknife 0.3

* Add R/readSampleTsvs.R:readSampleTsvs()

# swissknife 0.2

* Add R/plotting.R:plotBitScatter()

# swissknife 0.1

* Initial version
* add R/misc.R:sampleControlElements()