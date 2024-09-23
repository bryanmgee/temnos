# README for TEMNOS data file D4: Temnospondyl histology since 2000
## About

This is the README documentation for TEMNOS data file 4 (D4): Temnospondyl histology since 2000. This README file blends the style of a conventional software/data README file with a descriptor paper style of description. 

* Current version: 1.0.0 (initial release)
* Publication date: 2024/09/22

## Collection and standardization

All data in this dataset were collected manually from the literature. This includes articles, books, theses/dissertations (where available), posters, and preprints (except when novel taxa are being proposed). It records information on the sampled material, granularized to the level of distinct skeletal regions (as a model for augmentation in file D2), as well as basic bibliographic information about the publishing article. In contrast to files D2 and D3, each separate instance of a specimen (each article) is recorded as a separate entry.

## Caveats

Unlike files D2 and D3, the taxonomy has not been fully standardized against the framework in file D1, specifically for instances in which the original reported taxonomic identity of a specimen does not correspond to a presently valid taxon (e.g., '*Buettneria*', now synonymized with *Anaschisma*). The reason for this is that because histology is often an opportunistic enterprise, sampled material, mostly postcranial in nature, often contains no apomorphies, diagnostic features, or even differential features of a particular taxon, and the identity is instead often based on circumstantial evidence such as known taxonomic composition of a stratigraphic unit or locality. As a result, if the taxon a sampled specimen was originally referred to is no longer valid, it is less clear that it now pertains to a senior synonym or co-occurring taxon. The taxonomy is still standardized to higher levels (e.g., a specimen reported as *Buettneria* is still listed with full taxonomy down to Metoposauridae).

The dataset is intentionally (and semi-arbitrarily) restricted to histological sampling from 2000 onwards. A general time restriction is applied for a few reasons. Firstly, figures of more dated histological literature are intrinsically inadequate compared to contemporary works; in many instances, only vague aspects of the microanatomy can be reliably discerned. This is frequently exacerbated by the digital transformation of the original print forms and further reduction in quality. Secondly, methods for paleohistological sampling and imaging have advanced rapidly, including with respect to the use of methods and materials and collections practices that permit long-term physical stability of specimens. Even if the physical slides that were presented in historic literature can be relocated, they may no longer be of sufficient quality for reuse. As an index for potential histological resources, this dataset therefore focuses on the most recently produced materials that have the highest probability of being imaged at high resolution and of surviving in a physical form that can still be reused.

## Planned future augmentation

The following are areas where this data file is intended to be expanded. If you would like to contribute or suggest other areas, please refer to the CONTRIBUTNG.md document.

* Addition of metadata on sampling (e.g., completeness, sidedness of specimen; plane of sectioning; whether specimen photos are provided)
* Addition of metadata on data provisioning (e.g., whole section images vs. only close-ups; whether data are shared in external repository)
* Creation of similar datasets for CT analyses of temnospondyls (rare at present) and phylogenetic analyses
