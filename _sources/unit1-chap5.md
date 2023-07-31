# Chapter 5: Sensing and Responding to the Environment

:::{grid-item-card}
**Learning Objectives**

By the end of this chapter, students will be expected to:
1.	define what signal transduction means
2.	differentiate between one and two-component systems
3.	identify the sensor and response regulator of one and two-component systems
4.	describe how reporter plasmids are used to study response regulatory systems
5.	interpret data collected from the use of reporter plasmids and knock-out mutants
:::

## 5.1 Signal Transduction
Prokaryotes can sense numerous aspects of their environment including changes in chemical gradients, pH, osmolarity, light and magnetic fields. They also have the ability to respond to these sensations. Different sensing-response systems act over different time scales. Some sensations trigger an immediate change in behaviour without the synthesis of any new proteins while others require a change in gene expression because new proteins are required to respond to the sensation.

## 5.2 One and Two-component Systems

Sensing and responding to the environment involve protein-based signal transduction systems. There are two kinds of signal transduction systems: one-component and two-component systems (Fig 78) that we will introduce in this unit. We will introduce you to more systems in Unit 2. In prokaryotes, one-component systems are much more common than two-component systems.

```{figure} Figures/Unit_1/5-1.png
:name: Fig78
:height: 400px

One- and two-component signal transduction systems.
```

### 5.2.1 One-component system

A signal transduction protein is often thought-of as being composed of parts called domains (Fig 78). In one-component systems, a single protein serves two functions: one domain detects the signal (**sensor kinase**) and another domain initiates the cellular response (**response regulator**). For one-component systems, the signal is received directly by the binding of a small chemical from the environment (or a small chemical related to an environmental chemical) to the sensor kinase which is normally embedded in the plasma membrane (1). The signal activates its kinase activity which allows it to phosphorylate the response regulator to change its conformation so that it can actively bind to the DNA, specifically to the promoter region of genes that it regulates. This triggers a change in gene expression to either promote the production of proteins needed to respond to the sensation or even turn off the expression of proteins that may be making it respond negative to the change in environmental condition.  

### 5.2.2 Two-component system

In two-component systems, the two domains are separate proteins. The sensor detects the signal and interacts with a second protein which is the response regulator (Fig 78). The main difference between a two- versus one-component system is whether the two domains are separate proteins (two-component) or one protein (one-component). Note that in a one-component system, the response regulator is physically attached to the sensor which is membrane-bound but in a two-component system, the response regulator is free-floating in the cytoplasm. Therefore, in a two-component system, the response regulator can actively find and bind to its target whereas in a one-component system, the entire system is constrained to the membrane and either the system has to navigate around the membrane, and/or the DNA target has to shift to meet the response regulator (2). Two-component systems are not constrained and therefore can, in most cases, elicit a faster response. It is likely that this is a consequence of the evolution of one-component systems into a more efficient system like the two-component system. Still, in Bacteria, typically there are more one-component systems than two-components systems. This may be dependent on the types of responses and signals that have driven this evolution.  

### 5.2.3 Responses

For both one- and two-component systems, responses are specific dependent on the function of the output domain. There are three broad classes of output domains: those with enzymatic activity, those that bind to other proteins and those that bind to DNA to affect transcription and thereby gene expression. By far, the vast majority of output domains in prokaryotes bind to DNA so their primary role is to affect transcription and thus the synthesis of new proteins in order to mediate a cellular response. 

## 5.3 Knock-out Mutants and Complements

In this section, we want to explore techniques used by researchers to study signal transduction systems specifically through the use of **“knock-out” mutants and “complementation”** using laboratory-made plasmids. 

### 5.3.1 Knock-out Mutants

One of the ways we study regulatory systems in microbes is through the use of “knock-out” mutants. Knock-out mutants are laboratory derived strains in which the researchers have purposely deleted a gene of interest to see what happens to the phenotype that they are studying. For example, if a researcher is interested in seeing if *fliC*, a gene involved in flagellar biosynthesis, is involved in swimming motility, the researcher can knock-out *fliC* and look for the absence or inhibition of swimming (Fig 79). If the gene is essential for that phenotype, we normally expect the phenotype to be attenuated or absent in the mutant compared to the wild-type. In Fig 79, the absence of a flagella when *fliC* is knocked-out suggests that *fliC* is important in regulating flagella biosynthesis. 

```{figure} Figures/Unit_1/5-2.png
:name: Fig79

Example of a knock-out mutant of *fliC*, gene that encodes protein responsible for regulating flagella biosynthesis.
```

#### Laboratory Plasmids

Before we can talk about what a complement is, we need to understand what laboratory plasmids are. In Unit 1 Chapter 4, you explored the concept of plasmids as naturally occurring systems in Bacteria. Like so many different systems, we have harnessed plasmids which are naturally occurring in microbes as a technology that we can use in the lab and in research. There are two types of lab plasmids that we will discuss here: **expression plasmids and reporter plasmids**. The two primarily differ based on the purpose of use. 

Some general features of a plasmid (Fig 80) include: 

1. origin of replication (**Ori**): allows the plasmid to replicate independently of the chromosome
2. often two **selection/selectable markers**: this allows us to selectively grow the cells that have taken up the plasmid (this normally occurs through a form of horizontal gene transfer called transformation (Unit 1 Chap 4)). Types of selection markers can include antibiotic resistance genes or metabolic selector genes. 
3. **multiple cloning sites (MCS)**: these are regions where we can insert a target gene and/or target promoter region (this includes the operator). 

```{figure} Figures/Unit_1/5-3.png
:name: Fig80
:height: 300px

General plasmid map.
```

**Expression plasmids** are used to produce a protein of interest. The protein of interest does not necessarily need to be bacterial in nature. A **recombinant plasmid** is a type of expression plasmid that has another species’ protein cloned in it. For example, we can express the human insulin protein in *E. coli*! Because *E. coli* grows relatively fast, in theory, we can mass produce insulin through this method.

Expression plasmids normally have MCS in front of an existing promoter (Fig 81). The promoter is normally a promoter (like the lac operon promoter) in which the inducer is already known. This allows us to grow the bacteria on media that contains this inducer and forces expression of the protein of interest. You can also clone the gene of interest’s natural promoter and allow it to be expressed naturally, i.e. dependent on its own regulatory systems. 

```{figure} Figures/Unit_1/5-4.png
:name: Fig81

Comparing an expression and reporter plasmid. Note the yellow region as the cloning region of interest.
```

**Reporter plasmids** are a bit more challenging to understand. Contrary to expression plasmids, the goal of a reporter plasmid is not to express a gene of interest but instead to determine whether a gene of interest is being expressed. The promoter of the gene of interest is cloned in front of a reporter protein for which a read-out can be easily measured. The promoter will determine when and in what quantities the reporter protein is expressed. Two of the most common reporter proteins are the green fluorescence protein (GFP) derived from jellyfish in which you can measure fluorescence levels or the lacZ (beta-galactosidase) enzyme in which you can measure beta-galactosidase activity. In theory, the levels of your reporter protein, as detected by either fluorescence intensity or levels of beta-galactosidase activity, are an indicator that the promoter is either actively being transcribed or not. Therefore, you can use the reporter plasmid to determine conditions that activate expression of your target gene. This is a good technique for studying how a particular gene is regulated.

#### Complements

Deleting a gene from the chromosome can have unforeseen effects on various elements including growth, regulation and expression of other genes. To ensure that these side effects, also called **polar effects**, are not contributing to the phenotype loss that we see with a knock-out mutant, researchers often complement the mutant by re-introducing the original gene on an expression plasmid into the cell. The gene could have its own native promoter or an inducible promoter like the lac operon promoter where the researchers can force expression of that gene. The goal of the complement is to see if we can restore the phenotype by expressing the original gene in isolation, ie. not in the chromosome. If the phenotype is restored, we can more confidently attribute that the phenotype loss was due to that single gene deletion but if it is not restored, there may have been polar effects that were contributing to the phenotype loss that may not necessarily be because of the essentiality of our target gene in regulating the phenotype. Going back to the *fliC* example (Fig 82), by transforming the bacteria with an expression plasmid containing the wild-type *fliC* gene, we can see that the cells now have flagella which suggests that the phenotype in the knock-out mutant was truly because of *fliC* and not due to some polar effects that deleting *fliC* could on other genes. 

```{figure} Figures/Unit_1/5-5.png
:name: Fig82

Complementation of *fliC* restore the flagellated phenotype.
```

```{tip}
**Knock-out and Complement Nomenclature**

A typical convention for denoting a knock-out mutant is with the use of delta (Δ) in front of the gene(s) that has been deleted. Complements are normally denoted using a plus (+) sign after the gene that has been re-introduced into the cell using an expression plasmid.  
```

## Case Study: Metal Sensing

:::{grid-item-card}
This case study was adapted from: **Wosten et al., 2000**

Wosten MMM, Kox LFF, Chamnongpol S, Soncini FC, Groisman EA. 2000. A signal transduction system that responds to extracellular iron. Cell. 103: 113-125 

:::

**Overview**

In this case study paper, Wosten et al. were interested in studying 2 different two-component systems in the food-poison associated pathogen *Salmonella enterica*; both used to sense different metal ions. The PhoPQ system is an extensively studied two-component system that senses low levels of Mg2+. The PmrAB system is a less well-known system that senses high Fe2+ levels. In their model (Fig 83), they proposed a possibility that there is cross-talk between the two systems through PmrD. PmrD is up-regulated by PhoP and activates PmrB phosphorylation of PmrA.

Wosten et al. went about their research following a series of questions: 

```{figure} Figures/Unit_1/5-6.png
:name: Fig83

Model of 2 two-component systems, PhoPQ and PmrAB, used to sense different metal ions in S. enterica.
```

**Step 1: What signal(s) can be used to activate PmrA?**

The first thing Wosten et al. wanted to determine was what signal or signals were needed to activate PmrA (ie. phosphorylate PmrA). They created a reporter plasmid with the *pbgP* promoter cloned in it to determine levels of activated PmrA under different conditions. They collected the following data:

```{figure} Figures/Unit_1/5-7.png
:name: Fig84

A reporter plasmid was created using the promoter of *pbgP* in front of *lacZ* (beta-galactosidase). Beta-galactosidase activity as an indicator of *pbgP* expression was measured in low Mg or low Mg and high Fe in knock-out mutants of *pmrA, pmrB, phoP and phoQ*. The “No plasmid” control are WT *S. enterica* cells not transformed with the reporter plasmid.
```
:::{grid-item-card}
**Questions to consider:**

1.	Why did they use the *pbgP* promoter? Why not the *pmrA* promoter for their reporter plasmid?
2.	What happens when you knock-out *pmrA, pmrB, phoP, phoQ* to the model proposed in Figure 5.6?
3.	What is a no plasmid control? What is it supposed to test for? What does the data show for this control?
4.	Is there a treatment group that you would like to include?
5.	What signal(s) are needed to activate PmrA?
    a.	Low Mg2+ only
    b.	High Fe2+ only
    c.	Low Mg2+ AND high Fe2+
    d.	Low Mg2+ OR high Fe2+
:::

**Step 2: What genes could PmrA be regulating?**

Like many two-component system regulators, PmrA is promiscuous which means that it can bind to and activate or repress several different promoters of different genes. The researchers were interested in 5 different genes so they created reporter plasmids using the promoters of those genes to determine if PmrA was regulating them in a *phoQ* knock-out mutant.

```{figure} Figures/Unit_1/5-8.png
:name: Fig85


Beta-galactosidase activity measured in *S. enterica* transformed with reporter plasmids made using the promoters of *ugd, pbgP, pmrC, mgtA, or pcgL* cloned upstream of *lacZ* under low Mg or low Mg and high Fe conditions. 
```

:::{grid-item-card}
**Questions to consider:**

1.	Why did they do this experiment in a *phoQ* mutant and not the WT? 
2.	Why do you not see any signal in the low Mg2+ conditions? Is this expected?
3.	What does the beta-galactosidase activity measure?
4.	Which of the 5 tested genes are regulated by PmrA?
:::


**Step 3: Are the PhoPQ and PmrAB systems involved in antibiotic resistance?**

Interestingly, the genes that were found to be regulated by PmrA in Step 2 were all genes that had previously been reported to be involved in promoting antibiotic resistance. So, the researchers wanted to see whether the PhoPQ and PmrAB systems were involved in resistance against the antibiotic, Polymyxin B. They collected the following data:
 
```{figure} Figures/Unit_1/5-9.png
:name: Fig86

Percent survival of S. enterica WT, phoP knock-out, or pmrA knock-out treated with polymyxin B antibiotic under low Mg or low Mg and high Fe conditions.
```

:::{grid-item-card}
**Questions to consider:**

1.	Go back to the model in Figure 83 and match it up to which systems, PhoP or PmrA, would be activated in the *phoP and pmrA* mutants versus the WT under the two treatment conditions. 
2.	Which systems, PhoPQ or PmrAB, appear to promote resistance against Polymyxin B?
3.	Does one system promote better resistance than the other? If so, which one? How can you tell?

:::

 
## References

1.	Jung, H. et al. Twelve quick steps for genome assembly and annotation in the classroom. PLoS Comput. Biol. 16, e1008325 (2020).
2.	Mitrophanov, A. Y. & Groisman, E. A. Signal integration in bacterial two-component regulatory systems. Genes Dev. 22, 2601–2611 (2008).

