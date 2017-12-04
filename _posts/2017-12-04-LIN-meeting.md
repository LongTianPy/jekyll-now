---
layout: "post"
title: "Weekly LINbase meeting notes, 12/4/17"
---

## LIN meeting updates

Boris mentioned the hierarchy of metadata/LINgroup description, shown below.

- Level 1: Taxonomic Ranks
- Level 2: Intra-/Infra- species
- Level 3: Host range
- Level 4: Geographical information
- Level 5: Time

Taxonomic ranks | Intra-/Infra- species[^de67c72f] | Host range        | Geographical info | Time
----------------|----------------------------------|-------------------|-------------------|------
organism        | subspecies                       | host of isolation | continent         | year
superkingdom    | pathovar                         | host #2           | country           | month
phylum          | race                             | host #3           | region            | day
class           | biovar                           | host #4           |                   |
order           | genomospecies                    | host #5           |                   |
family          | phylogroup                       |                   |                   |
genus           | phylotype                        |                   |                   |
species         | serotype                         |                   |                   |
                | sequevar                         |                   |                   |
                | serovar                          |                   |                   |
|biotype         |                                  |                   |                   
|clade           |                                  |                   |                   


[^de67c72f]: There is no hierarchy applied to the names in "Intra-/Infra- species".

Bacteria, sharing one category of metadata, will be described as a LINgroup only if they belong to the same LINgroup described by another category of **upper-level** metadata.
For example: A group of bacteria can only be described as one intra-/infra- species if they belong to the same species.

Based on what we already have in the database table of `Interest` and `Attribute`, additional data will be updated.
