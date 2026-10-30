# Muscle-Contractility-NEB
**Name:** Pasculado, Mark Ryan T. 
**Date Completed:** October 30, 2026  
**Course:** Cell and Molecular Biology - B

## Assignment Details
**Gene:**  NEB —NM_001164508.2:c.19097G>T (p.Ser6366Ile) — ClinVar 496132 [missense]  
**Protein Accession:** NP_001157980.2  
**Protein Length:** 8,525 amino acids (aa)

## Process — R Workflow

<img width="1366" height="727" alt="R steps" src="https://github.com/user-attachments/assets/e6459a11-04c4-4eee-8877-0ee1468a2f3b" />

**Figure 1.** RStudio environment showing the complete script and its execution; no runtime errors, confirming the workflow runs successfully.

## Step 1 — Project Setup
gene_symbol = "NEB"
transcript_accession = "NM_001164508.2"
clinvar_id = "496132"
variant_protein = "p.Ser6366Ile"

## Step 2 — NCBI Gene Record
- Gene symbol: NEB
- NCBI Gene ID: 4703
- Official name: nebulin
- Chromosome: 2

## Step 3 — Protein Sequence
- NP accession: NP_001157980.2
- FASTA file: 
- Full R script:

## Step 4 — Amino‑Acid Composition

**Table 1.** Full amino‑acid composition of NEB (nebulin)
| AminoAcid | Count |
|-----------|------:|
| A | 632 |
| C | 69 |
| D | 655 |
| E | 522 |
| F | 138 |
| G | 284 |
| H | 255 |
| I | 460 |
| K | 1016 |
| L | 623 |
| M | 237 |
| N | 405 |
| P | 346 |
| Q | 422 |
| R | 354 |
| S | 552 |
| T | 412 |
| V | 500 |
| W | 134 |
| Y | 509 |

**Top 3 Most Abundant Residues:**
| Amino Acid | Count |
|------------|------:|
| K (Lysine) | 1016  |
| D (Aspartic acid) | 655 |
| A (Alanine) | 632 |

<img width="2400" height="1500" alt="01_amino_acid_composition" src="https://github.com/user-attachments/assets/3a4a51f5-46d4-4f3e-8166-fb455c98f0a9" />

**Figure 2.** NEB (nebulin) amino‑acid composition showing abundance of charged and large hydrophobic residues consistent with a cytoplasmic ion‑channel structure.

## Step 5 — ClinVar Record (Variation 496132)

<img width="1364" height="687" alt="Clinvar" src="https://github.com/user-attachments/assets/3a9e9dd7-e8ae-4281-95d0-054e3f628d94" />

**Figure 3.** ClinVar classification of NEB variant NM_001164508.2(NEB):c.19097G>T (p.Ser6366Ile), classified as a pathogenic.

## Step 6 — Second Biological Visualization

<img width="3000" height="900" alt="02_variant_position" src="https://github.com/user-attachments/assets/093f65d8-4e10-4821-8d8a-513dc5181028" />

**Figure 4.** Variant position plot showing p.Ser6366Ile at residue 6366 on the 8,525‑amino‑acid NEB reference protein.

## Step 7 — Explain the Molecular Mechanism
**1. Describe what your normal protein does in skeletal, cardiac, or smooth muscle (as appropriate). Identify whether it drives the actin–myosin cycle, regulates calcium, or maintains muscle structure.**  
- NEB encodes nebulin, a giant skeletal-muscle sarcomeric protein. It binds and stabilizes F-actin and helps regulate thin-filament length. Nebulin does not directly drive the actin–myosin cycle or regulate calcium; its main role is maintaining muscle structure.

**2. Explain what is known about the assigned variant, separating observed experimental evidence from computational prediction and clinical association.**
- **Variant Evidence — p.Ser6366Ile**

- **Clinical:** Classified Pathogenic by the ClinGen expert panel; associated with autosomal recessive nemaline myopathy.
- **Predictions:** REVEL score of 0.829, suggesting a potentially damaging effect on nebulin function.
- **Experimental:** Increased nebulin–actin binding affinity was reported, along with muscle abnormalities such as weakness, atrophy, and nemaline rods in a mouse model.

**3. Write a short causal chain: gene → protein → molecular function → assigned variant → possible effect on contraction, relaxation, or muscle integrity.**  
- NEB → Nebulin → F-actin stabilization and thin-filament organization → p.Ser6366Ile substitution → Potentially altered nebulin–actin interaction → Disrupted sarcomere organization and muscle integrity → Possible muscle weakness.

**4. Propose one experiment that could test your interpretation, such as ATPase measurement, calcium imaging, binding assay, microscopy, or force measurement.**  
- **Experiment: Immunofluorescence Microscopy**

Compare skeletal-muscle cells expressing wild-type and variant nebulin. Stain for nebulin and F-actin to observe their localization and organization within the sarcomeres.

**Expected Result:** If the variant disrupts nebulin function, variant-expressing cells may show altered nebulin localization or abnormal F-actin organization compared with wild-type cells.

## Questions to Answer in README.md

**1. What does your assigned gene encode, and how does this protein contribute to muscle function?**  
- NEB encodes nebulin, a large skeletal-muscle sarcomeric protein. Nebulin binds and stabilizes F-actin, helps regulate thin-filament length, and maintains sarcomere structure. It mainly supports muscle integrity and force generation rather than directly driving the actin–myosin cycle or regulating calcium.

**2. What was the exact protein accession and length retrieved with R?**
- Protein accession: NP_001157980.2
- Length: 8,525 amino acids

**3. What did the amino‑acid composition chart show? What can it NOT tell you?**

**4. What is your fixed ClinVar variant, and what is its current classification and evidence strength?**

**5. What is the scientifically supported mechanism linking this variant to muscle function, and what remains uncertain?**

**6. What additional experiment would help test the proposed mechanism?**  
