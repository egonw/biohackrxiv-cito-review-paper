---
title: 'BioHackEU23 report: The use of the Citation Typing Ontology in BioHackrXiv preprints'
title_short: 'BioHackEU23 #5: BioHackrXiv'
tags:
  - Citation Typing Ontology
  - BioHackrXiv
authors:
  - name: Egon Willighagen
    affiliation: 1
    orcid: 0000-0000-0000-0000
  - name: Et Al
    affiliation: 1
affiliations:
  - name: Dept of Biofinformatics - BiGCaT, NUTRIM, FHML, Maastricht University, The Netherlands
    index: 1
date: 8 November 2023
cito-bibliography: paper.bib
event: BH23EU
biohackathon_name: "BioHackathon Europe 2023"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Barcelona, Spain, 2023"
group: Project 5
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/egonw/biohackrxiv-cito-review-paper
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Egon Willighagen, Et Al
---


# Introduction

During the BioHackathon Europe 2021 we first starting working on Citation Typing Ontology (CITO,
[http://purl.org/spar/cito/2018-02-16](http://purl.org/spar/cito/2018-02-16))
support in BioHackrXiv articles [@citesAsAuthority:Willighagen2023CiTO].
We continued this development with a new template developed during the BioHackathon Europe 2022
([https://github.com/biohackrxiv/publication-template](https://github.com/biohackrxiv/publication-template)).
It extends on earlier work by the Journal of Cheminformatics [@citesAsAuthority:Willighagen2020Adoption],
which was the second journal with an article with explicit CiTO annotation,
and the first to pilot it for a wider audience [@citesAsDataSource:Willighagen2023Two].
Several other sources have been annotating citations with their intentions
too, resulting in over 400 articles having annotated citations, of which 31
have explicit annotations (see Figure 1) ([https://scholia.toolforge.org/cito/](https://scholia.toolforge.org/cito/)).

![Histogram showing the number of articles with annotated citations per year. Most citations come from datasets (green),
and more recently the Journal of Cheminformatics (purple). However, BioHackrXiv is a growing source of annotated citations (orange).](./citoOverTime.png)



# Citation Typing Ontology annotation


Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
