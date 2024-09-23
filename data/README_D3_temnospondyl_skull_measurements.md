# README for TEMNOS data file D3: Temnospondyl skull measurements
## About

This is the README documentation for TEMNOS data file 3 (D3): Temnospondyl skull measurements. This README file blends the style of a conventional software/data README file with a descriptor paper style of description. 

* Current version: 1.0.0 (initial release)
* Publication date: 2024/09/22

## Collection and standardization

All data in this dataset were collected manually from the literature, with the taxonomy then standardized to a consistent framework through file D1. This includes articles, books, theses/dissertations (where available), posters, and preprints (except when novel taxa are being proposed). It records information on the individual specimens' measured or estimated skull length as well as information about the geographic and temporal occurrence. It includes over 1,700 measurements from the literature, as well as single voucher rows for taxa for which no data are presently available. The specific page/figure/table/supplemental material that provides the measurement is provided for all entries.

## Caveats

The same limitations of the utilized taxonomic framework that were discussed for files D1 and D2 apply here as well. Unlike with file D2, this dataset is the result of a complete survey of all major clades, although this is not to say that it has captured every single reported skull length measurement in existence (it assuredly has not). The primary limitations of the present dataset are that the nature of the measurement (e.g., measurement vs. estimate; if estimate, on what basis; landmarks if measurement) is not recorded, so there is some intrinsic inconsistency among measurements related to the evolution of reporting standardized measurements in the literature. Some taxa also could probably be measured/estimated from visual data (e.g., figures, 3D models), but that data has yet to be incorporated. Additionally, some measurements are not vouchered by specific specimens but represent given ranges or bounds (e.g., "the smallest specimen measures 33 mm in skull length").

As with file D2, there are a small number of specimens that have been listed for different skeletal regions of different taxa in the literature and a different small set of specimens that are apparently not duplicates but that are catalogued with the same specimen number. As with files D1 and D2, Some specimens have been transferred to other collections and may presently have both a different institutional acronym and number than is recorded in the literature. Unless I could find a public source (museum database, literature, etc.) that specifically established how a particular specimen had been treated (rather than blanket statements or examples for another specimen from the same institution), the original specimen listing is given. 

## Planned future augmentation

The following are areas where this data file is intended to be expanded. If you would like to contribute or suggest other areas, please refer to the CONTRIBUTNG.md document.

* Addition of metadata indicating the nature of a measurement, including whether it is an empirical measurement or an estimate; if it is a measurement, from what landmarks; if it is an estimate, based on what element and what reference taxon/specimen/point. Certain attributes of a specimen, such as whether it is clearly distorted, are also intended to be added.
* Addition of incomplete specimens. The preserved length of specimens is sometimes provided as well, either in isolation or with an inferred length-when-complete; adding these specimens and a field to separate complete from incomplete specimens is also planned.
* Addition of other standard measurements. Although most contemporary literature only provides the midline skull length as a proxy of relative size, it was common in the mid- to late-20th century to provide a wide range of semi-standardized measurements (e.g., preorbital length, maximum width) that can also be harvested from the literature.
* Development and deployment of protocol for extracting measurement data from visual media to standardize collection of data from non-text means.
* Creation of separate dataset(s) for postcrania and whole body measurements/estimates.
