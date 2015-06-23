Outline for the comparative felidae project

**Goals** 

Study Feline evolution:

* Chromosome structure evolution: Felid-specific breakpoints, specie-specific breakpoints, genes involved into rearrangements
* Nucleotide sequence evolution - selection analysis - constrained elements, dN/dS
* Gene evolution - expansion, contraction, conserved genes, pseudogenes
* Evolution of repetitive elements: interspersed and tandem repeats, transposons
* Evolution of traits - genes involved into the traits development

**Multiple Alignments**

We are going to produce multiple alignments of feline species including several outgroups.
Among the available feline assemblies we choose those that were assembled at least into scaffolds. We are not aware about the availability of the Lynx genome, and the other Feline species are either were not sequenced yet or don't have a good quality assembly. 
The dog genome was selected as the closest outgroup for felines. The pangolin assembly is the outgroup to Carnivora family, we also included the primates lineage in order to perform comparison with the human genome.
Some alignments of these species have been already produced in the mouse strain project performed at UCSC. We are going to carry some of those including the rodent species (Mouse (reference assembly), Rat, Prarie vole, Egyptan Gerboa), two species from the Bovidae family and an elephant asembly as the other outgroups to the feline species in our project.

Felines:

* Domestic cat (FelCat 8.0)
* Cheetah
* African Lion
* Tiger
* Amur + Chineese Leopard
* Jaguar
* - Wildcat
* - Af & Asian lion
* - Snow Leopard
* ? Lynx
* -Florida panther  
* - Western Puma
* - Clouded leopard
* - Sunda Cl.Leopard 
* - Leopard cat
* - Fishing cat
* - caracal
* - Rusty Spotted cat
 
Outgroups:
* Dog
* Chinese pangolin
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
* - Malayan pangolin
* ? Hyena

**Synteny Analysis**

1. Synteny blocks and breakpoints. see [Synteny and rearangements](synteny.md)
 * Feline-specific breakpoints
 * Grimm Synteny can not evaluate synteny for too many species (5-6 maximally)
 * Summarize the pieces of software for synteny blocks
 
2. Rearrangements. see [Synteny and rearangements](synteny.md)
 * How to classify the rearrangements occured to the whole scaffolds
 * Try MGRA - ?
 * Most tools reconstruct the rearrangements _scenario_. It's hardly possible to check if the given scenario really took place. (It could be also multiple possible scenarios)
 
**MHC analysis**
 
**Selection Analysis**

1. Constrained elements
 * Combine GERP, phastCons
 * Figure out why GERP is so slow
 * Search for regions related for Feline specific genetic deseases and check if they are conserved
 * ? Rate of core eucaryotic genes that fall into constrained regions
 * Now gene coverage was calculated as intersection with mRNA (~70% for phastCons), try intersect with exons (CDS) only

2. dN/dS analysis

3. Compare copy number of some genes present in the feline genomes (like it was done in avian research for beta-keratins)

4. Traits
 * Diet
 * Fur, color
 * Skeletal structure - why some cats run faster, climbing facilities, way to fall down safely
 * Why do cats purr - The purr is produced through intermittent signaling of the laryngeal and diaphragmatic muscles - genetic bases
 * How domestication influenced the genome?
   * Domestic cats are very prone to the kidney desease - if the other cats are also prone to it?

*Gene analysis and TransMap* see [Annotation](https://github.com/felidae-reconstruction/doc/blob/master/annotation.md)

1. Gene evolution
 * map domestic cat gene annotation and cat's rnaseq data to other genomes
 (rnaseq will provide more confidence)
 * Gene expansion, contraction
 * Infer orthology and paralogy from the gene mapping
 * Pseudogenes - Ian's comparative gene annotator (recognize genes from pseudogenes)

2. Long non-coding RNAs 
 * We don't have long non-coding RNAs for cat and mapping them from those distant species like mouse or human can be difficult
 * There are short non-coding RNAs for the FelCat 6.2. (about 100bp)

3. Compare sizes of genomic element (exons, introns ..) to other species (s. [Comparative genomics reveals insights into avian genome evolution and adaptation](http://www.sciencemag.org/content/346/6215/1311.full))

*Repeats*

 Compare SINE, LINE, LTR, STR annotation - find common patterns in different feline genomes
 

