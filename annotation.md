# Genome Annotations
* Repeat
  - repeat masker with same library
* Ensembl set on Felis
  - http://www.ensembl.org/info/genome/genebuild/2013_01_cat_genebuild.pdf
  - Seems like poor coverage
  - | Biotype                 |  genes  | trans  |
    |-------------------------|---------|--------|
    | miRNA                   |     930 |    930 |
    | Mt_rRNA                 |       2 |      2 |
    | Mt_tRNA                 |      22 |     22 |
    | processed_pseudogene    |      24 |     24 |
    | protein_coding          |   19493 |  20259 |
    | pseudogene              |     518 |    518 |
    | rRNA                    |     901 |    901 |

* Genbank/RefSeq transcripts (UCSC felCat8)
  - | Type             | count |
    |----------------- |-------|
    | mRNA             |  2406 |
    | EST              |   919 |
    | RefSeq (NM/NR)   |   416 |

* retroposed genes identification
* protein coding gene conservation

* TransMap genes
* Investigate
  - http://genome.ucsc.edu/ENCODE/externalTools.html

# Ideas for building better gene annotations
- transmap + RNA-Seq (FC only) => AUGUSTUS hints
  - RNA-Seq needs mapped to FC 8.0
- cat<->human 94mya, cat<->mouse ???
- transmap will give us UTR and gene names
- vaidate genes for good gene structure
- compare with protein homology alignments
- compare with cat mRNA,EST
- assign stable id numbers for each transcript
- Ensembl from FC 6.2
  - based protein alignments, many from TREMBL
- Brian's human protein alignments
