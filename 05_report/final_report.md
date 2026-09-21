# Molecular Analysis of *FBN1* Mutations in Marfan Syndrome

**Student Name:** Jade Angela B. Suan

**Instructor:** Mr. Abner A. Bucol

**Course:** BIO-300 Cell and Molecular Biology

**Date:** September 21, 2026

**Gene:** *FBN1* (NM_000138.5 / NP_000129.3)

**Documented Variant:** c.8326C>T (p.Arg2776Ter) | ClinVar: VCV00016439.46

**Artificial Variant:** c.100delG

---

## Disease Background
Marfan syndrome is an autosomal dominant connective tissue disorder caused by pathogenic variants in the FBN1 gene located on chromosome 15 at 15q21.1 (Dietz, 2022). While primarily inherited from an affected parent, approximately 25% of cases arise from new spontaneous mutations (Milewicz et al., 2021). The condition affects roughly 1 in 5,000 individuals worldwide and manifests variably, predominantly impacting the cardiovascular, skeletal, and ocular systems. According to MedlinePlus, skeletal features commonly include a tall, slender build, disproportionately long limbs and fingers, chest wall deformities, and spinal curvature. Ocular findings may involve severe nearsightedness and lens dislocation while most critically, weakening of the aortic wall can lead to aneurysm or life-threatening dissection. Early diagnosis and consistent medical management greatly improve long-term outcomes. 
 
---

## Part I. Select a Human Disease and Gene

| Item | Details |
|---|---|
| Disease / Phenotype | Marfan Syndrome |
| Gene Symbol | FBN1 |
| Gene Name | fibrillin-1 |

---

## Part II. Research the Disease

### A. Disease

13. What is the disease or phenotype?
- Marfan syndrome is a genetic disorder that affects the body's connective tissue, which supports and structures bones, blood vessels, eyes, and organs.

14. What are its major clinical characteristics?
- Tall stature with long limbs/fingers (arachnodactyly), chest wall deformities (pectus excavatum/carinatum), joint hypermobility, lens dislocation (ectopia lentis), and aortic root dilation/dissection.

15. Which cells, tissues, or organs are mainly affected?
- Connective tissue throughout the body, specifically the aorta, heart valves, eyes, bones, ligaments, lungs, and dura mater.

16. What is its genetic basis?
- Genetic mutation in the FBN1 gene located on chromosome 15.

17. What is its inheritance pattern, if applicable?
- Autosomal dominant (50% chance of passing to offspring). About 25% of cases occur due to de novo (spontaneous) mutations.

---

### B. Gene and Normal Protein

18. What is the official gene symbol?
- FBN1

19. On which human chromosome is the gene located?
- Chromosome 15 (specifically 15q21.1)

20. What does the gene normally encode?
- Fibrillin-1 — an extracellular matrix glycoprotein

21. What is the normal biological function of the protein?
- Forms microfibrils in extracellular matrix to give structural support to elastic and nonelastic connective tissue throughout the body. It also controls signals that tell cells how to grow like the TGF-β pathway.

22. Where in the cell is the protein normally found?
- Extracellular matrix; outside the cell

23. In what biological pathway or cellular process does it participate?
- Extracellular matrix assembly, elastic fiber formation, and regulation of TGF-β cell signaling.

### C. Documented Mutation

| Detail | Information |
|---|---|
| Gene | FBN1 |
| Reference Transcript | NM_000138.5 |
| Reference Protein | NP_000129.3 |
| Exact Variant Notation | c.8326C>T |
| Nucleotide Change | At position 8326 in the coding sequence, cytosine (C) is replaced by thymine (T) |
| Predicted Protein Change | p.Arg2776Ter — Arginine at amino acid 2776 becomes a STOP codon |
| Mutation Type | Nonsense mutation — creates a premature stop codon without shifting the reading frame |
| ClinVar Accession | VCV00016439.46 |
| Clinical Interpretation | Pathogenic |
| Scientific References | Dietz HC et al. (1991). Marfan syndrome caused by a recurrent de novo mutation in the fibrillin gene. Nature 352: 337–339.<br>ClinVar accession (2024). VCV00016439 — FBN1 c.8326C>T (p.Arg2776Ter), NCBI.<br>https://www.ncbi.nlm.nih.gov/clinvar/variation/16439/

## Part III. Obtain the Normal Reference Sequence

| Item | Answers |
|---|---|
| Reference Transcript Accession | NM_000138.5 |
| Reference Protein Accession | NP_000129.3 |
| CDS | 317..8932 |
| CDS Length | 8,616 nucleotides |
| Predicted Protein Length | 2,871 amino acids |
| Start Codon | ATG |
| Stop Codon | TAA |
| Filename | FBN1_WT_CDS.fasta |

---

## Part IV. Import the Normal Sequence into Galaxy

**Figure 1.** Uploaded wild-type FBN1 coding sequence (FBN1_WT_CDS.fasta) in Galaxy history.

## Part V. Establish the Wild-Type Control

| Item | Answers |
|---|---|
| CDS length | 8,616 nucleotides |
| Predicted protein length | 2,871 amino acids |
| Start codon | ATG |
| Stop codon | TAA |
| Reading frame used | Frame +1 (F1) |
| First 10 amino acids | M R R G R L L E I A |
| Last 10 amino acids | L K M K I Q V L L H |
| Filename | FBN1_WT_protein.fasta |

## Part VI. Formulate a Mutation Hypothesis

| Item | Answers |
|---|---|
| Mutation and exact nucleotide change | c.8326C>T — Cytosine (C) is replaced by Thymine (T) at position 8326 of the FBN1 coding sequence (NM_000138.5). At the protein level: p.Arg2776Ter — Arginine at position 2776 is replaced by a premature STOP codon. |
| Number of nucleotide(s) affected | 1 nucleotide (single nucleotide substitution) |
| Predicted mutation type | Nonsense mutation |
| Predicted effect on the reading frame | No frame shift. Because this is a single base substitution (not an insertion or deletion), the triplet reading frame remains unchanged from the start codon up to position 2776. |
| Predicted effect on protein length | Protein will be shorter (truncated). Translation will terminate prematurely at codon 2776, producing a protein that is 2,775 amino acids long — missing the final 96 amino acids compared to the 2,871 aa wild-type protein. |
| Predicted effect on protein function | Loss of function. The C-terminal 96 amino acids are essential for proper protein folding, secretion, and assembly into microfibrils in the extracellular matrix. Without this section, functional fibrillin-1 levels drop, causing haploinsufficiency and the connective tissue pathology seen in Marfan syndrome. |

The c.8326C>T single-base substitution converts codon 2776 (CGA) into a premature stop codon (TGA) without shifting the triplet reading frame. Translation will terminate early at codon 2776, producing a truncated protein that is 2,775 amino acids long and missing the final 96 C-terminal residues. Loss of this essential C-terminal domain will disrupt proper protein folding, secretion, and microfibril assembly in the extracellular matrix, leading to haploinsufficiency and the connective tissue pathology characteristic of Marfan syndrome.

## Part VII. Create the Mutant Sequence

| Item | Recorded Value |
|---|---|
| Original nucleotide position(s) | c.8326 |
| Original sequence | C (codon: CGA) |
| Mutant sequence | T (codon: TGA) |
| Number of bases inserted | 0 |
| Number deleted | 0 |
| Number substituted | 1 |
| Mutation type | Nonsense (stop-gain) |
| Reference transcript | NM_000138.5 |
| Protein notation | p.Arg2776Ter |

## Methods
The wild-type FBN1 coding sequence (NM_000138.5) and protein sequence (NP_000129.3) were retrieved from NCBI and uploaded to Galaxy. The documented nonsense mutation (c.8326C>T) and an artificial 1-bp deletion (c.100delG) were edited into the CDS and translated using the Galaxy translation tool. Sequence alignments and length comparisons were performed to evaluate the reading frames and premature stop codons across all variants.

## Part VIII. Translate the Mutant Sequence

| Item | Value |
|---|---|
| Mutant CDS length | 8,616 bp |
| Mutant protein length | 2,775 amino acids |
| Reading frame | Frame 1 (+1) |
| First amino acid difference | Position 2776 (WT: Arg, Mutant: STOP) |
| Premature stop codon | Present at codon 2776 (TGA) |
| Amino acids affected | 96 residues (positions 2776–2871) not translated |
| Mutation type | Nonsense |
| Codon change | CGA (Arg) → TGA (Stop) at c.8326–8328 |

---

## Part IX. Compare WT and Mutant Proteins

24. At what amino-acid position do the sequences first differ?
- Position 2776. The wild-type protein contains Arginine (Arg/R), whereas the mutant sequence introduces a stop codon, so no amino acid is present.

25. Is only one amino acid affected?
- No. Position 2776 is changed from an amino acid codon to a stop codon; additionally, all 96 C-terminal amino acids (positions 2770–2871) are completely absent from the translated mutant protein.

26. Are multiple downstream amino acids changed?
- No. The reading frame remains unchanged, so upstream residues (1–2775) are identical to wild-type. Downstream amino acids are not changed, they are simply never translated because the stop codon ends translation early.

27. Was an amino acid deleted or inserted?
- No. This is a single-nucleotide substitution (C→T). No nucleotides were removed or added, so no amino acid is deleted or inserted at the DNA level.

28. Was a premature stop codon produced?
- Yes. Codon 2776 (CGA) was converted to TGA (stop codon), causing premature translation termination.

29. Did the reading frame change?
- No. A single base substitution does not alter the triplet reading frame. All codons before and after position 8326 are read in the same frame as wild-type.

30. Did the protein length change?
- Yes, the protein became shorter.
  - Wild-type length: 2,871 amino acids
  - Mutant length: 2,775 amino acids
  - Net change: Truncation of 96 amino acids from the C-terminus.

31. Is the mutation missense, frameshift, in-frame deletion/insertion, repeat expansion, or another type?
- Nonsense (stop-gain). The substitution converts an amino acid codon directly into a stop codon, causing premature termination.

## Part X. Explain the Molecular Consequence

### Mutation → DNA sequence change
The c.8326C>T mutation in the FBN1 gene is a single-base substitution at position 8326. The wild-type nucleotide at this site is cytosine (C); the mutant sequence is thymine (T). Only one nucleotide is replaced, there is no insertion, deletion, or change to the overall length of the coding sequence.

### Codon or reading-frame change
This substitution alters the first base of codon 2776, changing it from CGA to TGA. The reading frame remains completely intact because no bases were gained or lost; this is a substitution only. Every codon both before and after this position is read in the correct triplet frame.

### Protein sequence change
At the protein level, codon 2776 changes from CGA, which encodes the amino acid arginine, to TGA, which is a stop codon. As a result, translation stops prematurely at this position instead of continuing to the normal end of the transcript. The first 2,775 amino acids before position 2776 are identical between wild-type and mutant, but the final 96 amino acids that make up the C-terminal region of the protein are never translated at all. The wild-type protein is 2,871 amino acids long, while the predicted mutant protein is only 2,775 amino acids in length.

### Possible structural or functional change
The missing C-terminal region is essential for proper folding, stability, and secretion of fibrillin-1 from the cell. Without this region, the truncated protein is likely to misfold and be targeted for degradation; even if it partially produced, it cannot be efficiently secreted into the extracellular matrix or properly incorporated into the microfibril networks that give connective tissue its strength and elasticity. This means the mutant allele contributes little or no functional fibrillin-1, producing a state called haploinsufficiency where the single normal allele cannot make enough protein to meet tissue needs. Additionally, reduced microfibril formation removes the normal regulation of the growth factor TGF-β, leading to abnormally active further contributing to tissue damage and remodeling.

### Cellular consequence
With less functional fibrillin-1 available, microfibrils become sparse and weak throughout connective tissues. In the cells that line blood vessels, especially the aorta — and in cells that form supportive structures in the eyes, bones, and ligaments — the extracellular matrix loses its normal architecture and elasticity. Excess active TGF-β also drives abnormal cell growth and further weakens tissue structure.

### Disease or phenotype
These molecular and cellular changes lead directly to the characteristic features of Marfan syndrome: the aortic wall becomes progressively thinner and weaker, risking dilation and potentially life-threatening rupture; the fibers holding the lens in place weaken, causing lens dislocation; bones and joints grow excessively or become unusually flexible, resulting in tall stature, long fingers, chest wall deformities, and loose joints. Because only one altered copy of the gene is sufficient to reduce protein levels below the critical threshold, the condition is inherited in an autosomal dominant pattern.

## Molecular Interpretation: gene → mutation → protein → cellular effect → phenotype
**Pathway:** Gene (FBN1) → Mutation (c.8326C>T) → Protein (2,775 aa truncated fibrillin-1) → Cellular Effect (impaired microfibrillar assembly & excess TGF-β) → Phenotype (Marfan syndrome)

## Part XI. Second Experiment: Create Your Own Mutation

**Option chosen:** One‑nucleotide deletion (c.100delG)

### Prediction Before Translating
Deleting one nucleotide from the FBN1 wild‑type coding sequence at position c.100 will shift the entire reading frame starting at codon 34. Every subsequent codon will be read incorrectly, so the amino acid sequence will be completely different from that point onward. This will produce a very different and probably much shorter protein and will likely create a premature stop codon soon after position 33.

| Detail | Result |
|---|---|
| Deletion position | c.100 |
| Base deleted | Guanine (G) |
| CDS length after deletion | 8,615 bp (8,616 − 1) |
| Protein length after translation | 34 amino acids |
| First position of frameshift | Codon 34 (After amino acid 33) |
| Premature stop position | Codon 34 |
| Amino acids after position 33 | All completely different from wild‑type — no match |

## Part XII. Compare the Documented and Artificial Mutations

| Feature | Wild-Type<br>(FBN1) | Documented Mutation<br>(c.8326C>T) | Artificial Mutation<br>(c.100delG) |
|---|---|---|---|
| CDS length | 8,616 bp | 8,616 bp (no change) | 8,615 bp (shorter by 1 bp) |
| Protein length | 2,871 amino acids | 2,775 amino acids<br>(missing 96 at the C‑terminus) | 34 amino acids<br>(severely truncated) |
| Mutation type | — | Nonsense (single base substitution) | Frameshift (1‑base deletion) |
| Reading frame changed? | — | No, frame remains intact | Yes, shifted permanently from codon 34 onward |
| Premature stop codon appeared? | — | Yes, directly created at codon 2776 (CGA → TGA) | Yes, appeared unexpectedly at position 34 due to shifted frame |
| Amino acids affected | — | Positions 1–2,775 identical to WT; last 96 residues (2,776–2,871) untranslated | Positions 1–33 match WT; 2,838 residues after position 33 completely missing or scrambled |
| Expected functional consequence | Fully functional fibrillin‑1 forms microfibrils normally | Truncated protein fails to fold/secrete properly; causes haploinsufficiency leading to Marfan syndrome | Nearly entire protein sequence missing; transcript likely degraded via Nonsense‑Mediated Decay (NMD) with no functional product made |

Both mutations result in shortened, non‑functional protein products, but they operate through distinct molecular mechanisms:

1. **Nonsense Substitution (c.8326C>T):** Preserves the correct reading frame throughout 96.6% of the coding sequence. Residues 1–2,775 are synthesized normally, and translation halts prematurely at codon 2,776, removing only the final 96 C‑terminal residues.

2. **Frameshift Deletion (c.100delG):** Alters the triplet reading frame near the N‑terminus at codon 34. Every downstream codon is misread, rapidly introducing an out‑of‑frame stop codon at position 34 and terminating translation after only 34 amino acids.

A frameshift deletion near the 5' end of a gene is far more disruptive to protein primary structure than a late‑stage nonsense mutation. The specific type and genomic coordinate of a mutation dictate both the proportion of intact primary sequence retained and the overall biological severity of the lesion.

---

## Part XIII. Interpretation Questions

32. Why does the exact location of a mutation matter?
- The location determines how much of the protein stays normal and how much is altered. A mutation occurring early in the coding sequence affects nearly everything downstream, whereas a mutation near the 3' end only changes a small part. It also determines whether important functional regions are preserved or lost.

33. Why can deleting three nucleotides produce a different result from deleting one or two nucleotides?
- Nucleotides are read in triplets (codons). Deleting three nucleotides removes one codon, keeping the downstream reading frame intact so all other codons continue to be read correctly. Deleting one or two nucleotides shifts the reading frame entirely, so every codon after that is misread and the whole sequence changes.

34. Does every mutation change the amino‑acid sequence? Explain.
- No. Some substitutions change the DNA but not the amino acid; these are called synonymous or silent mutations, because more than one codon can code for the same amino acid.

35. Does every amino‑acid substitution destroy protein function? Explain.
- No. If a substituted amino acid possesses similar chemical properties to the original, the protein can still fold and work normally. Function is lost only if the change disrupts folding, structure, or an important active site.

36. Why can a frameshift affect many amino acids even if only one nucleotide was deleted?
- Because codons are read sequentially in groups of three. Removing one shifts the starting point of every codon that follows, resulting in an entirely different amino acid sequence downstream from that point.

37. Why might a premature stop codon produce a nonfunctional protein?
- Translation stops too early, so the protein is truncated, missing important sections needed for folding, stability or function. Shortened, misfolded proteins often cannot function properly and are rapidly targeted for degradation.

38. Could a mutation affect protein function without greatly changing protein length?
- Yes. A missense mutation alters a single amino acid without shortening protein length, yet it can severely disrupt active sites, ligand binding, or overall structural stability.

39. Could a mutation cause disease without changing the protein sequence? Give a possible molecular mechanism.
- Yes. Mutations in non‑coding regions, such as promoters, splice sites, or regulatory sequences can disrupt gene regulation, transcription rates, mRNA splicing, or transcript stability, without changing the amino acid sequence itself.

40. What evidence from your analysis supports the proposed molecular mechanism of your disease?
- The FBN1 c.8326C>T mutation changes codon 2776 from CGA (arginine) to TGA (stop codon), truncating the protein from 2,871 to 2,775 amino acids. Translation stops early, so the last 96 amino acids are never made. This missing region is essential for the protein to fold correctly, be secreted, and assemble into microfibrils in connective tissue. Less functional fibrillin‑1 is produced, and normal regulation of TGF‑β is lost, together these cause the weakening of tissues seen in Marfan syndrome.

41. Which conclusions are supported by your computational analysis, and which require evidence from published experimental studies?
- Directly supported by computational sequence analysis:
  - Wild‑type FBN1 coding sequence translates to 2,871 amino acids matching reference NP_000129.3.
  - c.8326C>T is an in‑frame nonsense mutation producing a truncated 2,775 amino acid protein.
  - c.100delG is a frameshift deletion at codon 34 that rapidly encounters an out‑of‑frame premature stop codon, yielding a 34 amino acid peptide.

- Requires evidence from published experimental/clinical studies:
  - That the truncated 2,775 aa protein is targeted for degradation or improperly secreted.
  - That haploinsufficiency or dysregulated TGF‑β signalling causes the clinical features of Marfan syndrome.
  - Confirming actual pathogenicity and phenotypic severity in human patients.

## Part XIV. Documentations

Galaxy Link: https://usegalaxy.org/u/suan_jade/h/suan-marfan-fbn1-mutation-lab

GitHub Link: https://github.com/Jayeyddi/Disease-Gene-Mutation-Lab/tree/main

## Limitations

* This analysis relies entirely on computational sequence data and does not include laboratory experiments such as protein expression, cell culture, or clinical observation.
* While the changes in DNA and amino acid sequence are predictable from the genetic code, actual protein folding, stability, secretion, and assembly into microfibrils would need to be confirmed through functional studies.
* Sequence data alone cannot determine how these variants affect tissues or symptoms in a living person.
* The artificial c.100delG deletion was created solely for educational comparison and is not a known naturally occurring mutation found in patients.
---

## Conclusion
This study demonstrates that not all genetic alterations produce the same effect, both the type of mutation and its location within the gene are critical in determining the outcome. The documented c.8326C>T nonsense substitution preserves the reading frame and leaves most of fibrillin-1 intact, only removing the final 96 amino acids and causing Marfan syndrome through haploinsufficiency. In contrast, the artificial one-base deletion at c.100 shifts the reading frame permanently after position 33, producing a severely truncated protein of just 34 amino acids that bears no resemblance to fibrillin-1 beyond the first 33 residues. This comparison clearly shows that a frameshift mutation early in the coding sequence is far more destructive than an in-frame change near the end. Understanding these differences helps explain why some genetic variants cause milder symptoms while others result in complete loss of protein function, providing important insight into how genotype relates to phenotype in human genetic disease.

---

## References

Dietz, H. (2022, February 17). FBN1-related Marfan syndrome. In M. P. Adam, J. Feldman, G. M. Mirzaa, et al. (Eds.), GeneReviews®. University of Washington, Seattle.
https://www.ncbi.nlm.nih.gov/books/NBK1335/

MedlinePlus. (2020, August 18). Marfan syndrome. National Library of Medicine.
https://medlineplus.gov/genetics/condition/marfan-syndrome/

Milewicz, D. M., Braverman, A. C., De Backer, J., Morris, S. A., Boileau, C., Maumenee, I. H., Jondeau, G., Van Eyk, K., & Pyeritz, R. E. (2021). Marfan syndrome. Nature Reviews Disease Primers, 7(1), 64.
https://doi.org/10.1038/s41572-022-00338-w

National Center for Biotechnology Information. (2024, August 22). ClinVar accession VCV00016439.46: NM_000138.5(FBN1):c.8326C>T (p.Arg2776Ter). U.S. National Library of Medicine.
https://www.ncbi.nlm.nih.gov/clinvar/variation/16439/

National Center for Biotechnology Information. (2026, February 5). Homo sapiens fibrillin 1 (FBN1), transcript variant 1, mRNA (NCBI Reference Sequence: NM_000138.5). U.S. National Library of Medicine.
https://www.ncbi.nlm.nih.gov/nuccore/NM_000138.5
