---
title: In-silico Construction of pPICZAwbe and pPIC3.5Kwbe
description: In-silico construction of pPICZAwbe and pPIC3.5Kwbe through the
  elimination of the α-factor signal peptide coding region from pPICZα A and
  pPIC9K, respectively.
date: 2022-01-17T07:25:58.471Z
---
| DOCUMENT TYPE              | PIC                           | RESEARCH PERIOD      |
| -------------------------- | ----------------------------- | -------------------- |
| THE SECOND SEMESTER REPORT | MUHAMMAD GHILDAN, YEPY RUSTAM | July – December 2021 |

### BACKGROUND

This experiment is aimed to construct pPICZAwbe and pPIC3.5Kwbe to be used for intracellular expression of *P. pastoris* transporter genes by removing the α-factor signal peptide sequence of pPICZα A and pPIC9K, respectively. The suggested method is based on the overlap-extension PCR (OE-PCR) through the amplification of the initial plasmids using the high-fidelity polymerase and a pair of primers designed to eliminate the α-factor signal peptide coding region while adding a short homologous sequence to both PCR product ends. The resulting linearized plasmids harboring a short homologous sequence at both ends is then directly transformed into E. coli DH5α competent cells to allow for homologous recombination to form a circular plasmid in vivo. Alternatively, the PCR product can be digested with EcoRI and self-religated using T4 DNA Ligase. The resulting plasmids are pPICZAwbe and pPIC3.5Kwbe having the sequence identical to the pPICZ B and pPIC3.5K, respectively. 

### OBJECTIVES

* To provide an experimental design of the construction of pPICZAwbe and pPIC3.5Kwbe by removing the α-factor signal peptide sequence of pPICZα A and pPIC9K, respectively.
* To provide the step-by-step workflow and verification methods.

### MATERIALS AND METHODS

The annotated DNA sequence of *Pichia pastoris* expression vectors pPICZα A and pPIC9K were obtained from [Addgene vector database](www.addgene.org). The maps of pPICZα A, and pPIC9K are shown in figure 1 and 9. The more detailed information of the plasmids used in this study is listed in table 1.

Table 1. List of genes and plasmid used or designed in this study.
| Name | Type | Description |
| --- | --- | --- |
| pPICZα A | Expression Vector | P. pastoris expression vector. The vector contains AOX1 promoter, α-factor signal peptide, Myc epitope tag, 6xHis tag, and AOX1 terminator flanking a cloning site. |
| pPIC9K |Expression Vector |P. pastoris expression vector capable of multi-gene expression. The vector contains AOX1 promoter, α-factor signal peptide, and AOX1 terminator flanking a cloning site. |
| pPICZAwbe | Modified Expression Vector |P. pastoris expression vector. The vector sequence is identical to pPICZ B and similar to pPICZα A but lacking the α-factor signal peptide. |
| pPIC3.5Kwbe | Modified Expression Vector | P. pastoris expression vector capable of multi-gene expression. The vector sequence is identical to pPIC3.5K and similar to pPIC9K but lacking the α-factor signal peptide. |

*In-silico* DNA sequence manipulation and visualization was performed using [Geneious v11.1.5 software](http://www.geneious.com), which included virtual DNA cloning (restriction and ligation), PCR simulation, sequence editing, sequence alignment, *in-silico* translation, and sequence annotation. Pairwise and multiple sequence alignment was performed with Global alignment with free end gaps method using Geneious Alignment algorithm. Primers were designed using the in-fusion cloning (Takarabio). Primers’ Tm were calculated using the Geneious software with SantaLucia 1998 formula. Extension of the Primer sequence was performed manually when needed. The primers were purchased from Macrogen Inc. (South Korea).

### RESULTS AND DISCUSSION

Experimental design to construct pPICZAwbe and pPIC3.5Kwbe by removing the α-factor signal peptide coding sequence from pPICZα A and pPIC9K using the  digestion-ligation method is described in the following sections.

The overlap-extension PCR (OE-PCR) method is used to amplify the desired region of plasmid template while removing the unwanted region, i.e., the α-factor signal peptide sequence. Each primer was extended with the homologous sequence to facilitate an *in-vivo* plasmid circularization in *E. coli* host cells after transformation. Therefore, the digestion and ligation steps in steps 0A02, 0A03, 0B02 and 0B03 can be be skipped by directly transform the PCR product (i.e., linear plasmid with homologous sequence at both ends) into *E. coli* host cells.

#### Elimination of α-factor signal peptide coding region from pPICZα A

The map of the initiating vector pPICZα A is shown in figure 1. The α-factor signal peptide sequence will be eliminated using the overlap-extension PCR (OE-PCR) method. 

![Map of pPICZα A](/assets/images/posts/0a00-ppicza-a-alphafactor.png "Map of pPICZα A")

*Figure 1. Map of pPICZα A. The vector contains AOX1 promoter, α-factor signal peptide, Myc epitope tag, 6xHis tag, and AOX1 terminator flanking a cloning site. The α-factor signal peptide sequence is annotated in light purple.*

##### Step 0A01 - Amplification of pPICZα A

Primers P15-AE-21_pPICZAwbe-F and P15-AF-21_pPICZAwbe-R are used to amplify the plasmid region by excluding the α-factor signal peptide coding sequence as illustrated in figure 2. 

![Positions of P15-AE-21_pPICZAwbe-F and P15-AF-21_pPICZAwbe-R in pPICZα A](/assets/images/posts/0A00-pPICZaA-primers.png "Positions of P15-AE-21_pPICZAwbe-F and P15-AF-21_pPICZAwbe-R in pPICZα A")
*Figure 2. Positions of P15-AE-21_pPICZAwbe-F and P15-AF-21_pPICZAwbe-R in pPICZα A.*

The PCR will produce a 3345-bp linear pPICZα A plasmid without the α-factor signal peptide coding sequence. A 17-bp homologous sequence is present in both ends of the product (see figure 3).

![linPICZα A-xαFactor = PCR product of pPICZa A lacking a-factor signal sequence (size = 3,345 bp). The product contains EcoRI sites at both ends.](/assets/images/posts/0A01-pPICZaA-PCRproduct.png "linPICZα A-xαFactor")
*Figure 3. linPICZα A-xαFactor = PCR product of pPICZa A lacking a-factor signal sequence (size = 3,345 bp). The product contains EcoRI sites at both ends.*

##### Step 0A02 - Digestion of linPICZα A-xαFactor with EcoRI

NOTE: this step can be skipped and directly proceed to step 0A04: transformation.

The PCR product from step 0A01 harbours EcoRI restriction sites at both ends. Therefore, EcoRI digestion will produce a fragment with two overhangs as illustrated in figure 4.

* Digestion of linPICZα A-xαFactor with EcoRI
* Fragment purification using PCR clean up kit (no need to perform gel extraction).

Figure 4. Digestion product of fPICZα A-xαFactor/EcoRI

##### Step 0A03 - Self ligation of fPICZα A-xαFactor/EcoRI

NOTE: this step can be skipped and directly proceed to step 0A04: transformation.

Ligation of the fPICZα A-xαFactor/EcoRI fragment from step 0A02 using T4 DNA ligase will produce a 3,328 bp circularized plasmid named pPICZAwbe as shown in figure 5.

Figure 5. Map of pPICZAwbe.

##### Step 0A04 - Transformation into E. coli DH5α competent cells

The PCR product from step 0A01 is transformed into E. coli DH5α competent cells using the standard protocol. Homologous recombination on the PCR product will create the circular pPICZAwbe (figure 5).

##### Step 0A05 - Plasmid Integrity Verification

Sequence alignment of pPICZAwbe and pPICZ A showed 3 gaps and 2 mismatches and additional XbaI restriction site at the non essential location. Therefore, it will not affect its functionality (see figure 6). In fact, the sequence is identical to pPICZ B (data not shown).

Figure 6. Alignment of pPICZAwbe and pPICZ A

###### Digestion

Digestion with HincII will discriminate between pPICZAwbe and the initiating vector pPICZα A. The digestion product of pPICZAwbe will produce 3 fragments (i.e., 74 bp, 783 bp, and 2471 bp), while pPICZα A will produce 4 fragments (i.e., 74 bp, 310 bp, 783 bp, and 2426 bp) as shown in figure 7.

Figure 7. Virtual gel electrophoresis of HincII digestion products of pPICZα A and pPICZAwbe. 100bp NEB ladder is used.

###### PCR

PCR of pPICZAwbe using P04-57-12_5-AOX1 and P04-11-10_3-end_AOX1 primers will produce a 324 bp PCR product (figure 8).

Figure 8. PCR product of pPICZAwbe (324 bp) vs pPICZα A (589 bp).

###### Sanger sequencing

Primers P04-57-12_5-AOX1 or P04-11-10_3-end_AOX1 flanking the modified sequence can be used to verify the elimination of α-factor sequence from pPICZα A.

#### Elimination of α-factor signal peptide coding region from pPIC9K

Figure 9. Map of pPIC9K. The vector contains AOX1 promoter, α-factor signal peptide, and AOX1 terminator flanking a cloning site. The α-factor signal peptide sequence is annotated in light purple.

##### Step 0B01 - Amplification of pPIC9K

Primers P15-AG-21_pPIC3.5Kwbe-F and P15-AH-21_pPIC3.5Kwbe-R are used to amplify the plasmid region by excluding the α-factor signal peptide coding sequence as illustrated in figure 10.

Figure 10. Positions of P15-AG-21_pPIC3.5Kwbe-F and P15-AH-21_pPIC3.5Kwbe-R in pPIC9K

The PCR will produce a 9,019-bp linear pPIC9K plasmid without the α-factor signal peptide coding sequence. A 15-bp homologous sequence is present in both ends of the product (see figure 11).

Figure 11. linPIC9K-xαFactor = PCR product of pPIC9K lacking α-factor signal sequence (size = 9,019 bp). The product contains BamHI sites at both ends.

##### Step 0B02 - Digestion of linPIC9K-xαFactor with BamHI

NOTE: this step can be skipped and directly proceed to step 0B04: transformation.

The PCR product from step 0B01 harbours EcoRI restriction sites at both ends. Therefore, EcoRI digestion will produce a fragment with two overhangs as illustrated in figure 12.

Figure 12. Digestion product of fPIC9K-xαFactor/BamHI

##### Step 0B03 - Self ligation of fPIC9K-xαFactor/BamHI

NOTE: this step can be skipped and directly proceed to step 0B04: transformation.

Ligation of the fPIC9K-xαFactor/EcoRI fragment from step 0B02 using T4 DNA ligase will produce a 9,004 bp circularized plasmid named pPIC3.5Kwbe as shown in figure 13.

Figure 13. Map of pPIC3.5Kwbe

##### Step 0B04 - Transformation into E. coli DH5α competent cells

The PCR product from step 0B01 is transformed into E. coli DH5α competent cells using the standard protocol. Homologous recombination on the PCR product will create the circular pPIC3.5Kwbe (figure 13).

##### Step 0B05 - Plasmid Integrity Verification

Sequence alignment of pPIC3.5Kwbe and pPIC9K showed an identical sequence (figure 14).

Figure 14. Alignment of pPIC3.5Kwbe and the original pPIC3.5K showing identical sequences along the vectors.

###### Digestion

Digestion with HincII will discriminate between pPIC3.5Kwbe and the original pPIC9K. Digestion of pPIC3.5Kwbe with HincII will produce 3 fragments (i.e., 1,041 bp, 2,422 bp, and 5,541 bp). In contrast, the digestion of pPIC9K with HincII will produce 4 fragments (i.e., 1,041 bp, 1,124 bp, 1,570 bp, and 5,541 bp) as shown in figure 15.

Figure 15. Virtual gel electrophoresis of HincII digestion products of pPIC9K and pPIC3.5Kwbe. A 1kb NEB ladder is used.
PCR
PCR of pPIC3.5K using P04-57-12_5-AOX1 and P04-11-10_3-end_AOX1 primers will produce a 221 bp PCR product (figure 16).

Figure 16. PCR product of pPIC3.5Kwbe (221 bp) vs pPIC9K (493 bp).

###### Sanger sequencing

Primers P04-57-12_5-AOX1 or P04-11-10_3-end_AOX1 flanking the modified sequence can be used to verify the elimination of α-factor sequence from pPIC9K.

### CONCLUSIONS AND FUTURE DIRECTIONS

The laboratory experiment of this study is yet to be performed. Therefore, the suggested method will be evaluated based on the experimental results. The OE-PCR proposed in this experimental design is much simpler and more straightforward than the conventional digestion-ligation cloning method and can be utilized for the deletion of a segment from or insertion of a short sequence into a plasmid.