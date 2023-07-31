# Chapter 4: Gene Expression and Regulation

:::{grid-item-card}
**Learning Objectives**

By the end of this chapter, students will be expected to:
1.	identify components of a prokaryotic gene and operon
2.	describe different ways that bacteria regulate gene expression at different levels of the Central Dogma
3.	predict how a gene may be regulated based on its structure and function
4.	predict the expression levels of the lac operon depending on the available substrate
5.	differentiate between vertical and horizontal gene transfer (HGT)
6.	describe each of the different types of HGT
7.	interpret and analyze data on the study of prokaryotic gene expression and HGT
:::

## 4.1 Genetic Organization

### 4.1.1 Genotype and Phenotype

The physical features and functional traits of an organism (its characteristics or **phenotype**) are a reflection of the proteins it possesses at any point in time. Indeed, almost every cellular process relies on the action/function of a particular protein or set of proteins. Proteins can be grouped into functional categories (Fig 56).

**Genotype** refers to the particular set of genes an organism possesses. A gene is the unit of genetic information, more concretely a segment of DNA that possesses the information specifying the order (= sequence) of amino acids in a polypeptide molecule or the sequence of nucleotides in a stable RNA molecule = transfer RNA (tRNA) or ribosomal RNA (rRNA). Remember that not all genes specify polypeptides. Some genes specify rRNA or tRNA as their final gene products.

```{figure} Figures/Unit_1/4-1.png
:name: Fig56
:height: 500px

Functional categories of proteins expressed in bacteria. 
```

```{note}
**Gene and protein names**

Prokaryotic genes are specified by a descriptive three letter designation (small letters, italicized or underlined) usually followed by an italicized or underlined capital letter; related genes are often given the same three letter designation followed by a different capital letter (Example: *rpsL*).
Prokaryotic proteins are given the same designation as genes except the first letter is capitalized and the designation is not written in italics or underlined (Example: RpsL). There are no “rules” for what genes/proteins can be called. This means it can be difficult to discern the function of a gene/protein from its designation. As far as eukaryotic genes and proteins go, there are different systems for different organisms.
```
An organism’s genotype resides in its **genome**. The term genome refers to the total physical DNA that specifies an organism’s characteristics, that is, all of its genetic material. It is composed of the DNA making-up an organism’s genes and the DNA between its genes. Genomics is the study and analysis of genomes. Proteome refers to all of the different proteins that can be synthesized by an organism. Proteomics is the study and analysis of proteomes. Bacterial genomes typically constitute its **chromosome** and **plasmids**. 


**Chromosome**

In eukaryotes, chromosomal DNA is generally linear and organellar DNA is generally circular. In prokaryotes, with few exceptions, all genome components are circular DNA molecules. The significance (if any) of linear chromosomes and plasmids in the few prokaryotes that possess them is not clear.

In most Bacteria, chromosomal DNA replication is initiated by proteins which bind at a specific nucleotide sequence called the origin of replication, *oriC* (Fig 57). DNA synthesis then proceeds in both directions (**bidirectionally**) around the chromosome to a termination region opposite *oriC* on the chromosome.

All prokaryotic genomes must have the same general classes of chromosomal genes, eg. genes encoding structural proteins, enzymes, transport proteins, DNA replication proteins, proteins for transcription and translation, regulatory DNA binding proteins as well as genes encoding tRNAs and rRNAs (Fig 56). different organisms have different mixes of genes within these classes (genotype) that endows them with particular characteristics and abilities (phenotype) linked to the microenvironments they have adapted to.
 
```{figure} Figures/Unit_1/4-2.png
:name: Fig57

Overview of semi-conservative, theta, bidirectional chromosome and plasmid replication in Bacteria. 
```


**Plasmids**

Interestingly, Bacteria contain genes outside of their chromosome. If you rupture a Bacterial cell, you will often find small circular pieces of DNA called plasmids (Fig 58). Most plasmids are not essential for the viability of their host under all environmental conditions but can augment a prokaryote’s ability to survive in certain circumstances. Indeed, plasmids are often grouped according to the genes that they carry and thus the characteristics they give the host organism in which they exist. Prokaryotic cells can host single or multiple copies of different plasmids at the same time. Some examples of different kinds of plasmids are given below.

- Resistance plasmids carry genes specifying proteins that confer resistance to antibiotics and other toxic chemicals like heavy metals.
- Nutrition plasmids carry genes which specify enzymes that allow organisms to use certain molecules as nutrients. These molecules are sometimes unusual chemicals in the environment (eg. petroleum, pesticides, PCBs) that are not essential for survival.
- Infection plasmids carry genes which specify proteins that are required for the establishment of infections in animals and plants.
- Symbiosis plasmids carry genes which specify proteins that are required for the establishment of symbiotic relationships with plants and animals.

```{figure} Figures/Unit_1/4-3.png
:name: Fig58
:height: 250px

Ruptured bacterial cell reveals chromosomal and plasmid DNA.
```

Plasmids are normally acquired through **horizontal gene transfer** (Section 4.5) which, in short, means that they can be acquired by a cell without it needing to divide (ie. reproduce) so the genotype of an existing cell can change without it needing to reproduce!

Many plasmids are replicated like the chromosome, beginning at an origin of replication with a specific nucleotide sequence termed *oriV* (Fig 57) followed by bidirectional complementary DNA synthesis around the double-stranded DNA (dsDNA) circle. This kind of replication is called theta bidirectional because the replicating chromosome/plasmid looks like the greek letter “theta”.


## 4.2 Gene Structure 

### 4.2.1 Individual Genes

Most prokaryotic genes are protein-encoding, that is, they specify a polypeptide rather than a stable RNA. A typical bacterial gene consists of (Fig 59): 
- a **promoter** region where the RNA polymerase binds during transcription.
- an **operator** region where a regulatory protein can bind. Depending on the type of regulation, it can either promote or inhibit transcription. This is discussed in more depth in Section 4.4.
- the **coding region** which contains the template for the mRNA. 
- and a **terminator** where the RNA polymerase falls off the DNA to end transcription.

```{figure} Figures/Unit_1/4-4.png
:name: Fig59

Prokaryotic gene and operon structure.
```

### 4.2.2 Operons

Besides individual genes, prokaryotic cells have also evolved to have **operons**, multiple genes under the control of a single promoter. In prokaryotes, it is common to find genes clustered together in the genome if they specify proteins that are involved in the same cellular process (Fig 60). Such gene clusters are called operons. The genes of operons are transcribed together as a single mRNA initiating at one promoter, but two or more different proteins with different amino acid sequences are translated from the single mRNA (Fig 59). 

```{figure} Figures/Unit_1/4-5.png
:name: Fig60
:height: 300px

Prokaryotic gene and operon structure.
```

## 4.3 Gene Expression

### 4.3.1 Transcription

**Initiation**

In Bacteria, transcription begins at a promoter, a region of dsDNA about 50 bp (base pairs) in size. Promoters have specific nucleotide sequences which RNA polymerase recognizes to initiate transcription. 

Bacteria have a single RNA polymerase. It exists in two forms: the **holoenzyme and the core enzyme**. The core enzyme has four subunits: two “alpha” subunits and two   very similar “beta” subunits (beta and beta-prime). In order to recognize and bind to a promoter sequence, the core enzyme must associate with a 5th protein called the sigma factor to form the holoenzyme (Fig 61). It is the sigma subunit that confers the ability to recognize a promoter sequence. In transcription initiation, RNA polymerase binds nonspecifically to DNA and then slides along it scanning for a promoter sequence. When one is detected, the polymerase stops, transcription is initiated, and the sigma subunit dissociates. There are several different sigma subunits in Bacteria, each with a different sequence specificity for promoter recognition. This allows Bacteria to regulate the transcription of entire categories of genes by controlling whether particular sigma factors are made.

```{figure} Figures/Unit_1/4-6.png
:name: Fig61
:height: 250px

Bacterial RNA polymerase consisting of the holoenzyme and sigma factor.
```

**Elongation**

Following the promoter is the coding region which acts as the template for the mRNA. After RNA polymerase binding to the promoter, RNA polymerase separates the DNA strands to gain access to the nucleotides of the template strand. The enzyme then moves along this DNA strand in the 3’ to 5’ direction synthesizing mRNA in the 5’ to 3’ direction using the nucleotide sequence of the template strand as guide for choosing the complementary nucleotides to link together. The first nucleotide copied into mRNA (the “+1 site”) occurs a few nucleotides “downstream” of the promoter.

**Termination**

There are at least two ways that transcription is terminated in Bacteria. These mechanisms are called intrinsic and factor dependent termination and are distinguished on the basis of whether protein factors are involved in termination. MICB 211 does not consider factor dependent termination. In intrinsic transcription termination, RNA polymerase falls off the template strand when it pauses over a stretch of weakly H-bonded A-U nucleotide pairs (Adenine in the template DNA and Uracil in the mRNA). RNA polymerase pausing is associated with the formation of a stem-loop structure in the mRNA that interacts with enzyme. This stem-loop structure is called an intrinsic transcription terminator.
 
### 4.3.2 Translation

**Initiation**

The nucleotide sequence of mRNA is used by ribosomes as a guide to link amino acids together in a particular sequence resulting in a unique polypeptide. To begin translation, ribosomes specifically bind to the mRNA at a nucleotide sequence called the **ribosome binding site (rbs)**. Ribosome binding sites can vary somewhat in sequence depending on the gene but all are about 5 nucleotides in length.

**Elongation**

After binding to the mRNA at the rbs, with the participation of tRNA, ribosomes move along mRNA in the 5' to 3' direction joining amino acids together via peptide linkages in the sequence specified by the nucleotide sequence in the mRNA (Fig 62). Several ribosomes can sequentially bind to and simultaneously translate the same mRNA, and translation can start even before mRNA synthesis is finished (Fig 63). During translation, the nucleotides are “read” by the ribosomes and tRNA in groups of three called **codons**. Codons specify the amino acids (AA) according to the genetic code.
 
```{figure} Figures/Unit_1/4-7.png
:name: Fig62
:height: 500px

Process of translation.
```
```{figure} Figures/Unit_1/4-8.png
:name: Fig63
:height: 300px

Multiple ribosomes bound to one mRNA molecule.
```
 
**Termination**

Polypeptides are synthesized from the N-terminus (first) to the C-terminus (last) so the 5' end of the mRNA coding region corresponds to the N-terminus of the polypeptide and the 3' end of the mRNA coding region corresponds to the C-terminus. When a ribosome encounters a stop or termination codon (UGA, UAA or UAG), translation terminates and the polypeptide is complete. 


## 4.4 Regulating Gene Expression

Proteins are expensive to make. Indeed, because the formation of each peptide linkage consumes 5 ATP (biological unit of energy) and proteins have hundreds of amino acids, translation of a single protein requires thousands of ATP molecules. In a world where nutrients are not always plentiful, it is not a good competitive strategy to make a protein or too much of a specific protein if it is not needed. This is a waste of nutritional resources.

Regulating gene expression means controlling when, where and how much of a particular gene product (usually a protein) is made. In this context, there are basically 4 types of gene expression; they are not necessarily mutually exclusive.

- **Constitutive (house-keeping) gene expression**: Some genes are expressed all the time because the product of the gene is required for a basic cellular function that is needed all the time.
- **Developmentally-regulated gene expression**: As part of a developmental genetic program, some genes must be expressed at different phases of a process or growth so that different proteins are made at different times. See example on endospore formation (Unit 1 Chap 3).
- **Cell-specific gene expression**: All cells that make-up a prokaryotic organism contain the same genetic information. Some genes are expressed only in certain cell types. 
- **Environmentally-regulated gene expression**: Some genes are expressed only under certain environmental conditions. 

This course will cover 4 ways that Bacteria control gene expression:

- Promoter strength
- Regulatory proteins 
- mRNA degradation
- Protein degradation

The mechanisms we cover in this course align with regulating gene expression at different stages of the Central Dogma of Biology (Fig 64). 

```{figure} Figures/Unit_1/4-9.png
:name: Fig64

Levels of gene regulation along the central dogma of biology.
```
 
### 4.4.1 Promoter Strength

**Promoter strength** refers to the frequency in which RNA polymerase initiates transcription. At strong promoters, transcription is initiated more frequently than at weak promoters.

In order to understand this, one has to appreciate that RNA polymerase binding to a promoter is not an “all-or-nothing” event. Although the enzyme binds to the promoter, it is also released. In other words, a dynamic binding equilibrium exists between the two states.

Although for a particular sigma subunit, all promoters have similar nucleotide sequences, they do exhibit some variation. This results in different RNA polymerase binding characteristics. At strong promoters, RNA polymerase spends more time bound to the DNA ( =higher **binding affinity**) than at weak promoters (=lower binding affinity) (Fig 65). The more time RNA polymerase spends bound to the DNA, the greater the likelihood that transcription will be initiated, the gene will be transcribed and the encoded polypeptide will be synthesized. That is, at strong promoters, transcription is initiated more frequently than at weak promoters, which results in more copies of mRNA per unit time and for this reason more polypeptide copies per unit time.

```{figure} Figures/Unit_1/4-10.png
:name: Fig65
:height: 200px

Promoter strength based on sequence variation.
```

### 4.4.2 Regulatory Proteins

Another way that microbes regulate gene expression at the DNA level is through the use of regulatory proteins. Regulatory proteins or **transcriptional regulators** are proteins that can actively bind to the operator region of the promoter and either inhibit RNA polymerase or recruit RNA polymerase depending on whether it is a **repressor or enhancer** of transcription respectively. 

Let’s explore the *lac* operon, for example. The lac operon contains genes that express enzymes involved in lactose metabolism. This means that the cell would only want to express these proteins when there is lactose, which the substrate, in the system. It would be wasteful for the cell to express these proteins when there is no lactose to metabolized. Therefore, the lactose molecules themselves help regulate when the lac operon is expressed or not. Upstream of the lac operon is the lacI gene which encodes for the transcriptional regulator, LacI. LacI is a transcriptional repressor which means that it binds to the operator region which is upstream of where the RNA polymerase and the sigma factor bind on the promoter, and it physically blocks the RNA polymerase from transcribing the lac operon. 

In the absence of lactose, LacI is bound to the operator preventing expression of the lac operon (Fig 66).

```{figure} Figures/Unit_1/4-11.png
:name: Fig66
:height: 500px

Negative regulation of lac operon by LacI repressor in the presence and absence of lactose
```
In the presence of lactose, the lactose molecule binds to the LacI regulator changing its conformation so that it cannot bind to DNA, this releases its repression on the lac operon promoter and allows RNA polymerase to transcript the lac operon genes and therefore express the lac operon enzymes (Fig 66). 

Let’s consider an extra layer of complication. Recall from Unit 1 Chap 3 that bacteria can selectively consume a substrate (ie. a sugar) that is preferred. Once they consume it, they subsequently begin to use a secondary, less preferred substrate. This results in diauxic (a growth curve with two exponential phases). 

In the context of the lac operon, consider that glucose which is often the preferred carbon source for most bacterial species is also present in the environment. The bacteria would not want to metabolize lactose as long as glucose is present and, therefore, the presence of glucose would affect the expression of the lac operon. From Fig 65, we can see that the lac operon is negatively regulated by the inhibitor, LacI, which is regulated by the presence or absence of lactose. 

Let’s look at Fig 67 now. Upstream of the lac promoter is another binding site called the CAP site. This is essentially another operator region bound by a secondary transcriptional regulator called CAP. CAP is regulated by a secondary metabolite: a small molecule called cAMP. The amount of cAMP produced is the cell is inversely related to the amount of glucose in the environment (i.e. more glucose equals less cAMP in the cell). cAMP binds to CAP allosterically changing its conformation so that it can actively bind DNA, specifically to the CAP site. CAP is an enhancer which recruits RNA polymerase to the promoter. Therefore, when CAP is bound, it promotes expression of the lac operon. But, we can’t forget that LacI exists too, so collectively these two systems regulate the lac operon based on lactose AND glucose levels. Consider Figures 66 and 67 and try to predict what the operon would look like if there was both lactose and glucose, only one of the sugars, or if both were absent.

```{figure} Figures/Unit_1/4-12.png
:name: Fig67
:height: 500px

Positive regulation of the lac operon with the enhancer, CAP, based on the levels of glucose.
```
 
|     Regulatory   protein    |     Operon   binding site    |     Relationship   to environment                                                       |     Overall   outcome                             |
|-----------------------------|------------------------------|-----------------------------------------------------------------------------------------|---------------------------------------------------|
|     LacI                    |     Lac promoter             |     Lactose binds LacI and inhibits its   repression effect                             |     High lactose   –> no lac operon repression    |
|     CAP                     |     CAP site                 |     Glucose   downregulates cAMP, cAMP binds CAP and increases its repression effect    |     High glucose   –> lac operon repression       |

### 4.4.3 mRNA Degradation

Another factor that impacts polypeptide copy number concerns how fast mRNA is degraded in a cell. Unlike stable RNA (rRNA and tRNA), mRNA is subject to enzymatic degradation by ribonuclease enzymes (RNases) as soon as it is made. This is why mRNA is called unstable RNA.

Different mRNAs have different half-lives in prokaryotic cells. Some have half-lives of about a minute while others have a half-lives of nearly an hour. Obviously the longer a mRNA lasts in a cell, the more polypeptide copies that can be translated from it; only a few copies of a polypeptide may be translated from a short-lived mRNA whereas 100s of copies of a polypeptide may be translated from a long-lived mRNA.

### 4.4.4 Protein Degradation

One of the most costly means of regulating gene expression in the cell is to directly degrade any proteins that the cell does not need. This process is the most costly because the cell has already spent the resources necessary to express and produce the protein. Proteins meant for degradation are normally tagged and sent to a large protease complex to be recycled back into their peptide or amino acid forms. 
 
## Case Study: Glucose-lactose Diauxie

:::{grid-item-card}
This case study was adapted from: **Inada et al., 1996**

Inada T, Kimata K, Aiba H. Mechanism responsible for glucose-lactose diauxie in *Escherichia coli*: challenge to the cAMP model. Genes to Cells: 1:293-301
:::

**Overview**

What we call scientific concepts are not perfect. As we continue to collect data, we often find ourselves refining or redefining these “concepts”. The lactose-glucose model of regulating expression of the lac operon is one of these concepts that have evolved over the years. In this paper, published in 1996, we want to explore what evidence they collected that defined an older model of how we believed the lac operon was regulated and compare it to how we know it works today. In this paper, Inada et al. are exploring how cAMP is potentially regulating the *lac* operon in different levels of lactose and glucose. We know how it works now but they didn’t quite define it yet in 1996. Let’s see if their data aligns with our modern model of this system. 

**Step 1: Testing different levels of glucose and lactose**

```{figure} Figures/Unit_1/4-13.png
:name: Fig68
:height: 400px

Beta-galactosidase levels as an indication of activation/expression of the *lac* operon and total cAMP levels under 4 conditions. Glycerol is a poor carbon source for *E. coli*.
```
:::{grid-item-card}
**Questions to consider:**

1.	What do you think is the purpose of the glycerol treatment?
2.	Considering what you know about the lac operon model today, what is unexpected in terms of the beta-galactosidase activity? Which treatments don’t meet the expected results?
3.	Considering what you know about the lac operon model today, what is unexpected in terms of the cAMP levels? Which treatments don’t meet the expected results?
4.	According to the data, what condition(s) trigger expression of the lac operon?
5.	According to the data, what condition(s) trigger increase in cAMP levels?
:::

**Step 2: cAMP or no cAMP conditions**
```{figure} Figures/Unit_1/4-14.png
:name: Fig69

Growth measured in OD600 and beta-galactosidase activity under a condition where cAMP is added to the media at high levels and a strain that in unable to produce cAMP.
```
:::{grid-item-card}
Questions to consider:

1.	Do the growth curves align to what you would have expected considering what you know about how the lac operon works today? What is different?
2.	Does the beta-galactosidase activity align to what you would have expected considering what you know about how the *lac* operon works today? Why or why not?
:::


## 4.5 Horizontal Gene Transfer (HGT)

An inherent feature of the Darwinian Tree of Life concept is the exclusivity of vertical descent, that is, offspring obtain genes from their parent(s). However, it has become clear that organisms can also obtain genes from nonparental sources as well. This is called **horizontal gene transfer (HGT)** to distinguish it from vertical descent = **vertical gene transfer (VGT)** (Fig 70). In HGT, the organism that donates DNA is the **donor** and the organism that receives the DNA is the **recipient**.

```{figure} Figures/Unit_1/4-15.png
:name: Fig70
:height: 300px

Horizontal versus vertical gene transfer.
```

In this course, we will cover 3 mechanisms of HGT (Fig 71):

1.	Transformation
2.	Transduction
3.	Conjugation

```{figure} Figures/Unit_1/4-16.png
:name: Fig71
:height: 400px

Different forms of HGT. Blue: donor cell; Red: recipient cell. 
```
 
### 4.5.1 Transformation

The transport of “naked” donor DNA from the environment into a recipient is known as transformation. When Bacteria die, they can lyse, releasing their DNA and other cytoplasmic contents into the environment. Because the chromosome is very large and physically fragile, when it is released from dead cells, it breaks up into 100's of linear pieces or fragments with an average length of about 20-100 kb. This means each “average” fragment carries about 20-100 “average” genes. These DNA fragments can be taken-up by other (recipient) cells.

In order to transport DNA from the environment, Bacteria have to be in a specific physiological state called the **competent state**. In the competent state, proteins for the transport of DNA from the environment are synthesized. These proteins are designated in different ways in different Bacteria. In MICB 211, the proteins or the transport of DNA will be referred to as Com proteins (encoded by com genes) which is the common practice for bacteria with a Gram-positive cell wall. Some Bacteria always synthesize Com proteins and are always competent whereas others become competent as a result conditions in the environment such as nutrient limitation or other stresses such as exposure to damaging radiation or chemicals. 

### 4.5.2 Transduction

The transfer of DNA from a donor to a recipient mediated by a virus, specifically a **bacteriophage**, that can result in a change in the phenotype of the recipient is called transduction. 

Bacteriophage	Like other viruses, bacteriophage or “phage” are infectious particles of genetic material wrapped in a protein coat. Tailed dsDNA phage particles possess protein capsids sometimes called heads. They also possess a protein tail with protein tail fibres. Their coiled bodies are used like a syringe to inject their DNA into the bacterial host (Fig 72). 

```{figure} Figures/Unit_1/4-17.png
:name: Fig72
:height: 200px

Structure of a typical bacteriophage. 
```
Binding of a phage particle to the cell surface receptor initiates the infection process. In the case of a common type of bacteriophage called T4, the phage DNA is injected into the host cell cytoplasm and the remainder of the T4 phage particle remains on the cell surface (Fig 73).

```{figure} Figures/Unit_1/4-18.png
:name: Fig73
:height: 400px

T4 bacteriophage lytic and lysogenic lifecycles.
```
Following the injection of phage DNA into the bacteria, depending on the conditions and type of phage, the bacteriophage can undergo two different lifecycles (Fig 73). In the lytic lifecycle, the phage forces the host to expresses its own viral proteins allowing for virus particles to assemble inside the host until it lyses the cell to release the newly formed particles into the environment. In the lysogenic lifecycle, it integrates its viral DNA into the host chromosome and stays in a dormant state until certain conditions trigger the lytic lifecycle. 

When the new phage particles are being packaged in the host, there is a chance that fragmented host, bacterial DNA is packaged into the phage head by mistake. This is where transduction can occur because this phage containing accidental bacterial DNA can go on and infect another bacterial cell and transfer that DNA to a new host. A phage particle containing only host DNA is referred to as a transducing phage. 

```{figure} Figures/Unit_1/4-19.png
:name: Fig74
:height: 500px

Bacterial transduction mediated by bacteriophage.
```

### 4.5.3 Conjugation

Conjugation refers to the transfer of a plasmid from one prokaryote to another by cell- to-cell contact. Like phage, plasmids are a kind of selfish genetic element that can “infect” host cells. Unlike phage however, plasmids exist only inside prokaryotic cells, they do not have an extracellular state.

About 25% of plasmids can directly transfer themselves from one organism to another by cell-to-cell contact in a process called conjugation. In conjugation, the plasmid-containing organism is called the donor and the organism receiving the plasmid is called the recipient. Although conjugation has been documented between two bacteria with different cell wall types, studies have mostly focused on conjugation between two unicellular Proteobacteria both with Gram-negative cell walls or two unicellular Firmicutes both with Gram-positive cell walls.

Conjugative plasmids possess DNA transfer or tra genes that encode transfer (Tra) proteins required to mediate the conjugative transfer of plasmid DNA from one cell to another. Many types of plasmids can possess tra genes. 

Initial contact between the donor and the recipient is made with conjugation pili (Fig 75). The proteins that compose conjugation pili are specified by some of the tra genes of the conjugative plasmid in the donor. Three kinds of conjugative pili have been described: Type IV pili, F-pili, and P-pili.

```{figure} Figures/Unit_1/4-20.png
:name: Fig75
:height: 500px

Plasmid conjugation.
```

### 4.5.4 Fate of HGT DNA

**Plasmids**

Plasmids can be introduced into a recipient cell via conjugation or transformation. Because plasmids are stable, independently replicating entities that can work autonomously from the chromosome, depending on the plasmid’s compatibility with the host, it can sit stably within the cytoplasm (Fig 76). Also dependent on the host, genes encoded on the plasmid can be expressed to affect the host phenotype. 
 
```{figure} Figures/Unit_1/4-21.png
:name: Fig76

Fate of plasmid and ssDNA transferred via HGT.
```

**ssDNA Fragments**

The usual fate of single-stranded (ss) donor DNA is to be degraded into nucleotides by nucleases specific for ssDNA normally present in bacterial cells. Occasionally ss donor DNA fragments escape degradation because they interact with the protein RecA. If this happens there is the potential for the donor DNA to become integrated into the recipient chromosome (Fig 4.21). It depends on whether the donor DNA and recipient chromosomal DNA share homology. When two regions of DNA exhibit a high degree of nucleotide sequence similarity, they are said to be homologous. If two molecules of DNA share a region of homology of at least a few hundred nucleotides, the two molecules may become joined together at the region of homology by a process called **homologous recombination**. Homologous recombination is mediated by the RecA protein. Besides RecA, enzymes with endonuclease (nickase) and ligase activities are involved in the process. This would allow the DNA fragment to incorporate itself into the chromosome and depending on the host conditions, those genes may be expressed to alter or affect the host phenotype. 


## Case Study: Transferring toxins through transduction

:::{grid-item-card}
This case study was adapted from: **Park and Park, 2021**

Park D, Park J. Characteristics of bacteriophage isolates and expression of Shiga toxin genes transferred to non Shiga toxin producing *E. coli* by transduction. J. Microbiol. Biotechnol. 31(5):710-716
:::


**Overview**

Shiga toxin is a type of bacterial toxin produced by *Escherichia coli* and *Shigella dysenteriae* that can cause diseases in both humans and animals. Not all strains of *E. coli* can produce this toxin, but there is a concern that environmental bacteriophages are helping to transfer this toxin gene to non-toxin producing *E. coli* via transduction. Park and Park hypothesized that strains of phage carrying Shiga toxin that were most effective at infecting *E. coli* would also result in the highest rate of transduction. 

 
**Step 1: Testing different phages against non-toxin containing *E. coli* strains**

The authors looked at two types of Shiga toxin genes, *stx1 and stx2*. They tested 9 different phage variants against 5 different non-toxic strains of *E. coli*.

**Table 4.1**. Infection detection of 9 different Stx-encoding phage (each row) against 5 different non-toxic strains of *E. coli* (each column). + infection detected, - infection not detected. 
```{figure} Figures/Unit_1/table4-1.png
:name: table4-1
```

:::{grid-item-card}
**Questions to consider:**

1.	How do you compare what is considered high infection rate versus low?
2.	Which phage variants had the lowest infection rate? Which had the highest?
3.	Are there strains of *E. coli* that were more susceptible to infection? more resistant? 
:::

**Step 2: Detecting the Shiga toxin genes in *E. coli* strains**

**Table 4.2**. Detection of two types of Shiga toxin genes chromosomally in originally non-toxic E. coli strains. In brackets, the phage variant which infected the strain is indicated.
```{figure} Figures/Unit_1/table4-2.png
:name: table4-2
``` 
 
:::{grid-item-card}
**Questions to consider:**

1.	Which phage variants had the lowest infection rate? Which had the highest?
2.	Are there strains of *E. coli* that were more susceptible to infection? more resistant? 
3.	Does this data correspond to the data in Table 4.1 when it comes to infectivity of phage and susceptibility of *E. coli* strain?
4.	Which gene appears to be transferred more often through transduction?
:::


**Step 3: Detecting Shiga toxin production induced by osmotic pressure**

In the last step, Park and Park wanted to look at the actual levels of toxins being secreted. They hypothesized that the production of Shiga toxin is dependent on salt concentration as osmotic pressure could induce Shiga toxin production. They measured the number of viable stx1 and stx2 containing *E. coli* cells and level of the Stx1 and Stx2 toxins with increasing salt concentrations as follows:  

```{figure} Figures/Unit_1/4-23.png
:name: Fig77
:height: 400px

Shiga toxin levels (*stx1 and stx2*) and bacterial cell viability with increasing salt concentration.
``` 

:::{grid-item-card}
**Questions to consider:***

1.	Is Shiga toxin production reliant on osmotic pressure (ie. salt concentration)? If it is, is there an optimal condition for production of each Shiga toxin? 
2.	What is the relationship between cell viability and salt concentration? Why do you think this relationship exists the way that it does?
3.	What is the relationship between cell viability and Shiga toxin production if any?
:::
