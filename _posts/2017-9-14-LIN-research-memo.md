---
layout: "post"
title: "Research memo"
---

#### Research memo
- Confirmed: There is no case with ANI<0.3 and cov<0.7, which confirms how ANI is calculated: only considers those alignments whose cov>0.7 & identity>0.3
- But tons of cases whose ANI's pretty high but cov<0.7.
- When only looking at ANI pairs whose cov>70%, the linear correlation between ANI and estimated ANI is much better, 0.994.
- Among 280 pairs which are filtered out but having > 95% ANI, only 3 pairs not in the same species. Even more, 2 of the pairs belong to genera Escherichia and Shigella, and 1 pair belongs to Agrobacterium genus.
- Confirmed, as long as it's > ANI 95%, however coverage is, belongs to the same species.
- What makes us confuse is the part that we cannot assign a 95% level LINgroup using MinHash because there's no Jaccard similarity reported.
- Check tax ID from metadata, index=4, maybe use data mining to dig the taxonomy out.
