---
layout: "post"
title: "Notes for LIN meeting"
---
# Meeting notes
- Chengjie talked about the issues and things to improve he's found in the website ([see here](https://longtianpy.github.io/meeting)).  
- Long will finish adapting the website to the new database schema next week, and work on converting Taxonomy ID to LINgroups after that, hopefully done in another 2 weeks.  
- Boris also has some new thoughts about the extension of identification functionality.

### Website functionalities
1. #### Identification
    - ##### Identification with whole genome sequence
      The user has the whole genome sequence of a bacterial isolate and wants to know what it is and the LINgroup/taxonomic rank it belongs to. The __whole LIN assignment workflow will be performed__ but will __not__ write to the database once is done. The user __may or may not__ want to add this genome to the database after receiving the identification result, so we need to leave him/her an option. If he/she wants to add this genome to the database, we will check if the metadata are enough and let him/her finish the submission table.
    - ##### Identification with gene sequences
      The user only has sequences of a few genes of an isolate. Like what we already have so far, the user copy and paste a gene sequence and the sequence will be BLASTed against the database. The result will show, predicted by the alignment of one gene, what LINgroup this isolate belongs to. Currently we don't allow this kind of identification with multiple gene sequences, which may give a more accurate prediction, not sure if we want to go further on this. Two functions that are nice to have: 1) drag a file contains the gene sequence and drop on the textbox, the gene sequence shows up; 2) word limit, to avoid the user accidently put the whole genome in to the textbox.
2. #### Genome upload
   Unlike identification using the whole genome, the user knows it when he/she choose this function that this genome will be recorded in the database along with the taxonomic information & isolation information, so the user needs to fill pretty much every field in the submission form __(we can come back and talk about this later)__. 
3. #### Search database
    Keep the function as is. Improvement regarding to performance may be made.
  

