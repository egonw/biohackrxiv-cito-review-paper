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
[http://purl.org/spar/cito/2018-02-16](http://purl.org/spar/cito/2018-02-16), [@citesAsAuthority:usesMethodIn:CiTO])
support in BioHackrXiv articles [@citesAsAuthority:Willighagen2023CiTO].
We continued this development with a new template developed during the BioHackathon Europe 2022
([https://github.com/biohackrxiv/publication-template](https://github.com/biohackrxiv/publication-template)).
It extends on earlier work by the Journal of Cheminformatics [@citesAsAuthority:Willighagen2020Adoption],
which was the second journal with an article with explicit CiTO annotation,
and the first to pilot it for a wider audience [@citesAsDataSource:Willighagen2023Two].
Several other sources have been annotating citations with their intentions
too, resulting in over 400 articles having annotated citations, of which 31
have explicit annotations (see Figure 1, [https://scholia.toolforge.org/cito/](https://scholia.toolforge.org/cito/)).

![Histogram showing the number of articles with annotated citations per year. Most citations come from datasets (green),
and more recently the Journal of Cheminformatics (purple). However, BioHackrXiv is a growing source of annotated citations (orange).](./citoOverTime.png)

# Citation Typing Ontology annotations

In this paper we review how *BioHackathon Europe 2022* authors have been using CiTO annotations.
The authors took benefit from the CiTO support for Markdown developed by Krewinkel *et al.*
[@usesMethodIn:Krewinkel2017Formatting].
At the time of writing, eight articles were associated with this 2022 edition of BioHackathon Europe
that had CiTO annotations (see Table 1,
[https://scholia.toolforge.org/venue/Q123154374](https://scholia.toolforge.org/venue/Q123154374)).

Table: Overview of *BioHackathon Europe 2022* reports with CiTO annotations.
Percentages indicate the number of citations with an intention other than `cito:cites`.

|**Article** |**Intentions** | **%CiTO** |
------------ |------------ |---
An ETL pipeline to construct the Intrinsically Disordered Proteins Knowledge Graph (IDP-KG) using Bioschemas JSON-LD data dumps [@citesForInformation:Ammar2022ETL]|cito:extends, cito:usesDataFrom, cito:usesMethodIn|71%|
BioHackEU22 Project 22: Plant data exchange and standard interoperability [@citesForInformation:Arend2022BioHackEU22]|cito:citesAsAuthority|100%|
BioHackEU22 Report for Project 16: Make your own or favourite software available on your cluster with EasyBuild/EESSI [@citesForInformation:Moretti2023BioHackEU22]|cito:citesAsAuthority|100%|
Empowering the community with notebooks for bespoke microbiome analyses [@citesForInformation:Rogers2023Empowering]|cito:citesAsAuthority, cito:usesDataFrom, cito:usesMethodIn, cito:citesAsPotentialSolution|100%|
An evaluation of EDAM coverage in the Tools Ecosystem and prototype integration of Galaxy and WorkflowHub systems [@citesForInformation:Lamothe2023evaluation]|cito:usesDataFrom, cito:usesMethodIn, cito:describe|100%|
Streamlining data brokering from Research Data Management platforms to ELIXIR Repositories [@citesForInformation:D2023Streamlining]|cito:citesAsAuthority, cito:usesDataFrom, cito:usesMethodIn|100%|
Improving Metadata Collection and Aggregation in Plant Phenotyping Experiments with MIAPPE Wizard and DataPLANT [@citesForInformation:Arend2023Improving]|cito:citesAsAuthority|100%|
BioHackEU22 Report: Enhancing Research Data Management in Galaxy and Data Stewardship Wizard by utilising RO-Crates [@citesForInformation:Eguinoa2023BioHackEU22]|cito:citesAsDataSource, cito:discusses, cito:usesMethodIn|100%|

# Discussion

In retrospect, only seven different intention types have been used (see Figure 2). This is fewer than in the articles
published in the *Journal of Cheminformatics* [@citesAsDataSource:Willighagen2023Two], but the total
number of articles is also lower. Similar, however, is the willingness of authors in their
willingness to annotate citations: most articles have all citations typed with their intentions.
Only one article had two citations annotated with the already implied `cito:cites`.

![Bubble chart with the citation intentions used by the *BioHackathon Europe 2022* papers.](./citationIntentions.png)




## Acknowledgements

We thank the authors of the six *BioHackathon Europe 2022* papers for annotation of their citations.

## References
