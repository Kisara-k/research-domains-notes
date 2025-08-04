## Microbial Genes in the Human Genome: Lateral Transfer or Gene Loss?

[Salzberg et al. 2001](https://d396qusza40orc.cloudfront.net/genintro/misc/Salzberg-etal-2001-Science.pdf)

## Study Notes

### Abstract

The human genome was analyzed for evidence that genes had been laterally transferred into the genome from prokaryotic organisms. 

Protein sequence comparisons of the proteomes of human, fruit fly, nematode worm, yeast, mustard weed, eukaryotic parasites, and all completed prokaryote genomes were performed, and all genes shared between human and each of the other groups of organisms were collected. 

About 40 genes were found to be exclusively shared by humans and bacteria and are candidate examples of horizontal transfer from bacteria to vertebrates. 

Gene loss combined with sample size effects and evolutionary rate variation provide an alternative, more biologically plausible explanation.

### 1. 🧬 Introduction to Microbial Genes in the Human Genome

This study explores a fascinating question in genomics: **Are some genes found in the human genome actually transferred from microbes, specifically bacteria, through a process called lateral (or horizontal) gene transfer?** Traditionally, gene transfer was thought to occur only vertically—from parent to offspring. However, in microorganisms, genes can jump between unrelated species, a process known as **lateral gene transfer (LGT)** or **horizontal gene transfer (HGT)**.

The specific hypothesis under investigation is called the **Bacteria to Vertebrate Transfer (BVT) hypothesis**, which suggests that hundreds of bacterial genes might have been incorporated into the human genome during vertebrate evolution. This idea is intriguing because it implies that bacteria could have permanently altered the human genome, potentially even manipulating it for their own benefit.


### 2. 🔬 Background and Scientific Question

Historically, gene flow between species was considered rare and mostly limited to closely related species. But studies of microorganisms revealed that bacteria can exchange genes widely, including genes for antibiotic resistance, across distant species. This discovery raised the possibility that such gene transfers might also occur between bacteria and vertebrates, including humans.

The **scientific question** driving this research is:  
**How strong is the evidence that the 223 bacterial-like genes found in the human genome were actually laterally transferred from bacteria to vertebrates?**

This question challenges previous claims that these genes are the result of lateral transfer, proposing instead that other evolutionary processes might explain their presence.


### 3. 🧪 Methods: How the Study Was Conducted

To investigate this, the researchers compared protein sequences (proteomes) from humans and a variety of other organisms, including:

- Prokaryotes (bacteria and archaea)
- Eukaryotes such as fruit fly, nematode worm, yeast, mustard weed, and several parasites

They used two major human protein datasets:  
- The **Ensembl proteome** (31,780 proteins)  
- The **Celera proteome** (26,544 proteins)

Using a tool called **BlastP**, they searched for human proteins that had close matches in bacterial genomes but were absent in nonvertebrate eukaryotes. Genes found only in humans and bacteria but not in other eukaryotes were considered candidate BVT genes.


### 4. 📉 Results: What the Data Showed

Initially, about **40 genes** were identified as candidates for lateral transfer from bacteria to humans. However, as the researchers included more nonvertebrate genomes in their analysis, the number of candidate BVT genes **decreased significantly**. This suggests that many genes initially thought to be unique to humans and bacteria were actually present in other eukaryotes but had been missed due to incomplete genome data or annotation errors.

After filtering and reanalysis, the number of candidate BVT genes dropped to:  
- 114 genes (Ensembl set)  
- 89 genes (Celera set)

Further analysis reduced these numbers even more, eventually identifying only **41 genes** as strong candidates for lateral transfer.


### 5. 🔍 Alternative Explanations: Gene Loss and Sampling Bias

The researchers proposed three main alternative explanations for the presence of these bacterial-like genes in humans:

#### 5.1 Gene Loss  
Many genes present in a common ancestor of eukaryotes may have been lost in some lineages over time. For example, yeast and mustard weed have undergone extensive gene loss. This means that a gene found in humans and bacteria but missing in other eukaryotes might not be due to lateral transfer but because those other eukaryotes lost the gene.

#### 5.2 Sampling Bias  
The genomes of nonvertebrate eukaryotes currently available are limited and biased toward certain groups (animals, plants, fungi). This limited sampling can make it seem like some genes are unique to humans and bacteria when they might be present in other, unsequenced eukaryotes.

#### 5.3 Rate Variation in Nucleotide Substitution  
Genes evolve at different rates in different species. Some genes mutate quickly in certain lineages, making them harder to detect by sequence similarity alone. This can cause false negatives in identifying homologous genes in nonvertebrates, again making it appear that genes are unique to humans and bacteria.


### 6. 🌳 Phylogenetic Analysis: Testing the BVT Hypothesis

If lateral gene transfer from bacteria to vertebrates had occurred, the transferred genes should be more closely related to their bacterial donor lineage than to other prokaryotes. This relationship can be tested by building **phylogenetic trees**—diagrams showing evolutionary relationships.

The researchers built trees for candidate BVT genes and found that most did **not** cluster with any specific bacterial lineage. Instead, the gene trees were consistent with **normal vertical inheritance** (passed down from common ancestors) and explained by gene loss or rate variation.

For example, the human **hyaluronan synthase (HAS)** genes, previously suggested as bacterial transfers, showed evolutionary patterns consistent with normal inheritance rather than lateral transfer.


### 7. 🧩 Addressing Data Limitations and Annotation Issues

The absence of a gene in a genome database does not guarantee the gene is truly missing. Reasons include:

- Some genomes are incomplete.
- Gene annotation (identifying genes in DNA sequences) is still ongoing and imperfect.
- Some genes might be present but not yet recognized.

To address this, the researchers used **TBlastN** searches (protein sequences against nucleotide sequences) to find genes that might be missing from annotations. This further reduced the number of candidate BVT genes.


### 8. 🔬 Final Results and Conclusions

After extensive filtering, reanalysis, and consideration of alternative explanations, the researchers concluded:

- Only about **41 genes** remain as plausible candidates for lateral transfer from bacteria to humans.
- The majority of the initially proposed 223 bacterial-like genes are better explained by **gene loss, limited sampling of nonvertebrate genomes, and rate variation in gene evolution**.
- The evidence for widespread lateral gene transfer from bacteria to vertebrates is weak.
- The simpler explanation (following **Ockham’s razor**) is that these genes were inherited vertically and lost in some lineages, rather than transferred laterally.


### 9. 🧠 Broader Implications and Scientific Approach

This study highlights important principles in genomics and evolutionary biology:

- **Hypotheses must be tested rigorously**, considering alternative explanations.
- **Data completeness and quality** are crucial for accurate conclusions.
- **Phylogenetic analysis** is a powerful tool to distinguish between vertical inheritance and lateral gene transfer.
- Extraordinary claims, like widespread lateral gene transfer between bacteria and humans, require strong evidence.
- The study exemplifies scientific skepticism and the iterative nature of research, where initial findings are refined and sometimes overturned by more comprehensive data and analysis.


### Summary

In summary, this research critically examined the claim that hundreds of bacterial genes were laterally transferred into the human genome. By comparing human genes with those of many other organisms, considering gene loss, sampling bias, and evolutionary rate variation, the authors showed that most of these genes are not the result of lateral transfer. Instead, they are better explained by traditional evolutionary processes. Only a small subset of genes remains as candidates for possible lateral transfer, but even these require further study.