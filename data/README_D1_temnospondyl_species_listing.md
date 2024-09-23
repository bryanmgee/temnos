# README for TEMNOS data file D1: Temnospondyl species listing

## About

This is the README documentation for TEMNOS data file 1 (D1): Temnospondyl species listing. This README file blends the style of a conventional software/data README file with a descriptor paper style of description. 

* Current version: 1.0.0 (initial release)
* Publication date: 2024/09/22

## Collection and standardization

All data in this dataset were collected manually from the literature, with the taxonomy then standardized to a consistent framework. It records information on the taxonomic authority, type specimen(s) and what type these specimens are, and the countries where the specimen(s) was collected and where it is reposited. Taxonomic authority is recorded as the Version of Record (VOR), which is usually the electronic version in the digital era, so the same literature may be cited differently in this dataset compared to other datasets for which the pagination (and thus the print version) is the necessary record. The present version of this file includes three core statues: Valid, Disputed (either the species is clearly valid, but the genus placement is debated, or the species validity is questioned), and invalid (Nomen dubium, Nomen nudum, Nomen vanum). Disputed taxa indicate which rank is being disputed. 

For invalid names, the original name is listed, even if the taxon has been listed with other names or synonymized with another taxon. For example, *Metopias stuttgartensis*, now considered a nomen dubium for indeterminate metoposaurid fragments, has also been listed in the literature as *Metoposaurus stuttgartensis*; *Metoposaurus* remains a valid genus for other species. Here, *M. stuttgartensis* is listed with *Metopias.* Several species of *Parotosaurus* (replaced by *Parotosuchus* for presently valid species) have a similar configuration.

## Caveats

The taxonomic framework presented here is internally standardized so that it can be used to standardize that of the other data files, but there are obviously areas within the conceptual framework of temnospondyl taxonomy that remain disputed, such as the usage of Capitosauroidea versus Mastodonsauroidea or the validity of certain taxa (e.g., '*Broiliellus*' *hektotopos*). Given the structure of the data file, there is no way to presently record all possible frameworks in an effective way that still permits efficient use of the data. That various debates about temnospondyl taxonomy are not directly recorded in the file should not be misconstrued as a personal opinion of consensus; in most instances, I have defaulted to what I perceive as the predominating framework, although there are instances in which no clear consensus emerges. Reusers less familiar with the literature should note that Russian taxa in particular tend to be more disputed in validity and taxonomic placement because Russian workers often utilize different taxonomic frameworks (which is not a remark on which is more 'accurate'). 

Rare instances of "split holotypes" (where multiple parts of a single individual designated as the holotype are catalogued as separate specimens at separate institutions) are recorded in a fashion that may be suboptimal for some analyses. For example, the holotype of *Edops craigi* is FMNH UR 336 and MCZ 1201. Only FMNH UR 336 is listed in the fields for institution and specimen number; MCZ 1201 is noted only in the Notes field. Not listing each specimen as a separate entry with the same taxonomic information avoids double-counting if summarizing some fields (e.g., how many valid temnospondyl species are there) but introduces undercounting if summarizing other fields (e.g., how many type specimens are reposited at the MCZ). All split holotypes are noted in the Notes, so it would be possible to edit the data to account for this.

Some holotypes have been transferred to other collections and may presently have both a different institutional acronym and number than is recorded in the literature. Unless I could find a public source (museum database, literature, etc.) that specifically established how a particular specimen had been treated (rather than blanket statements or examples for another specimen from the same institution), the original specimen listing is given. For example, UT-BEG (University of Texas, Burea of Economic Geology) collections were folded into TMM (Texas Memorial Museum) collections, but the available data (e.g., literature) do not clearly show that the holotype of *Broiliellus olsoni*, UT-BEG 31189.8, was transferred with the same number or renumbered, so the original number is listed here. As there are other instances in which the specimen number was definitively changed in addition to the acronym (e.g., UCLA VP 3686 to UCMP 203686 for *Nanobamus macrorhinus*), a static specimen number should not be assumed. The same applies to the formulation of specimen numbers that may include other characters like punctuation or letters.

## Planned future augmentation

The following are areas where this data file is intended to be expanded. If you would like to contribute or suggest other areas, please refer to the CONTRIBUTNG.md document.

* Inclusion of junior synonyms and outdated combinations, with metadata on the "authority" that first proposed a change in status of a name. Note that this work is largely completed but needs to be standardized before its release.
* Inclusion of bibliographic information for naming papers.
* Inclusion of etymological data for genera and species.
* Cross-linking with file D2 (temnospondyl specimen listing) to record and categorize what skeletal region(s) a type specimen pertains to.
