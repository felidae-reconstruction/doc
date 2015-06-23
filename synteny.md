# Synteny and Rearrangements
* References:
  - Mingfu Shao and Bernard M.E. Moret 
    Comparing genomes with rearrangements and segmental duplications
    Bioinformatics (2015) 31 (12): i329-i338 doi:10.1093/bioinformatics/btv229 
    http://bioinformatics.oxfordjournals.org/content/31/12/i329.full
    - new paper (Jun,2015) in bioinformatics. Suggest linear programming algorithm
  - Cristina G. Ghiurcuta and Bernard M. E. Moret
    Evaluating synteny for improved comparative studies
    Bioinformatics (2014) 30 (12): i9-i18 doi:10.1093/bioinformatics/btu259 
    http://bioinformatics.oxfordjournals.org/content/30/12/i9.full
* Software:
  - GRIMM-Synteny http://grimm.ucsd.edu/GRIMM/
    - Hannenhalli-Pevzner algorithms for computing unichromosomal and multichromosomal genomic distances
    - Ksenia had problems with larger number of genomes
  - DRIMM http://bix.ucsd.edu/projects/drimm/
    - DRIMM algorithm extends the GRIMM-Synteny algorithm towards the problem of identifying the synteny blocks in highly duplicated genomes.
    - in C#, Linux version planned, but not yet available
    
  - SyMAP was used in the tiger paper (10.1038/ncomms3433)
    - Desktop application. It is not able to work with the large data - fails with the memory error.
  
  - Satsuma Synteny, SyntenyTracker were used in the comparative avian genome analysis (see supplement to 10.1126/science.1251385)

  - Ragout  use https://github.com/fenderglass/maf2synteny
    Limited to <= 20 genomes; default synteny block scale is 5000. According to some input from Son we try using different scales.

