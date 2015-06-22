Outline for the comparative felidae project

**Multiple Alignments**

Felines:

* Domestic cat
* - Wildcat
* Cheetah
* African Lion
* - Af & Asian lion
* Tiger
* - Snow Leopard
* Amur Leopard
* Jaguar
* ? Lynx
* -Florida panther  
* - Western Puma
* ? Clouded leopard
* - Sunda Cl.Leopard 
* - Leopard cat
* - Fishing cat
* - caracal
* - Rusty Spotted cat
 
Outgroups:

* ? Hyena
* dog
* Chinese pangolin
* - Malayan pangolin
* human
* Elephant
* Mouse (reference assembly)
* Rat
* Prarie vole 
* Egyptan Gerboa
* Human
* Chimp 
* Gorilla
* Orang
* Resus macaque
* Rabbit
* Sheep
* Cow

**Analysis**

1. Synteny blocks and breakpoints
 * Feline-specific breakpoints
 * Grimm Synteny can not evaluate synteny for too many species (5-6 maximally)
 * Summarize the pieces of software for synteny blocks
 
References:
* Evaluating synteny for improved comparative studies 10.1093/bioinformatics/btu259

 
2. Rearrangements
 * How to classify the rearrangements occured to the whole scaffolds
 * Try MGRA - ?
 * Most tools reconstruct the rearrangements __scenario___. It's hardly possible to check if the given scenario really took place. (It could be also multiple possible scenarios)
 
References:
* Comparing genomes with rearrangements and segmental duplications http://bioinformatics.oxfordjournals.org/content/31/12/i329.full - brand new paper (Jun,2015) in bioinformatics. Suggest linear programming algorithm
 
3. Constrained elements
 * Combine GERP, phastCons
 * Figure out why GERP is so slow
 * Search for regions related for Feline specific genetic deseases and check if they are conserved
 * ? Rate of core eucaryotic genes that fall into constrained regions
 * Now gene coverage was calculated as intersection with mRNA (~70% for phastCons), try intersect with exons (CDS) only

*Gene analysis and TransMap* 
4. Gene evolution
* map domestic cat gene annotation and cat's rnaseq data to other genomes
 (rnaseq will provide more confidence)
* Gene expansion, contraction
* Infer orthology and paralogy from the gene mapping
* Pseudogenes - Ian's comparative gene annotator (recognize genes from pseudogenes)

5. Long non-coding RNAs 
 * We don't have long non-coding RNAs for cat and mapping them from those distant species like mouse or human can be difficult
 * There are short non-coding RNAs for the FelCat 6.2. (about 100bp)

6. Traits
