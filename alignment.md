# Alignments

* cactus

* [mus-strain tree](mus-strain-1504.nh)

* grafting HAL files
  - extract the fasta(s) for the root(s) of the subtree(s) you want to use from the mouse alignment
  - include those as leaves in the proper place in your new alignment
  - run your alignment
  - use halAppendHalSubtree to append the relevant parts of the mouse hal to the cat hal
  - use halRemoveGenome to remove the mouse strains

* UCSC Chains and Nets
