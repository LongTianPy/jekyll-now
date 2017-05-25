---
layout: "post"
title: "Dev-update @ 5/24/2017"
---
Copied from previous dev update

#### Problems found
- ~~GenomeProfile was using out-dated database.~~ solved on 5/23/17
- The way UserProfile page lists submitted genomes is not friendly at all.
- Highlighting selected LINgroup is not available in SubmissionResult page.
- ~~When clicking on a row in searchProcessView2, the page will proceed to GenomeProfile in the current tab. We need it be able to open that page in a new tab.~~ Solved on 5/23/17
- Edit page seems to be wrong
- BLAST function isn't working properly... Karan will be working on it.

#### New stuff
- Dropdown menu for LINgroup in searchProcessView2 page created. Will direct to LINgroup details and show members in current page/search.
- ~~Developing LINgroup detail page.~~ Page created on 5/23/17
- ~~Need to figure out a way to show members in the current page.~~ No longer need it
- Add popups for indicating threshold of each position. But it's not very nice. Popup comes with Bootstrap looks good, but it will make the LINs after that position shift left, which is very weird.
