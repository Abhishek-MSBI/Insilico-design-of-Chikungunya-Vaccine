# 🧬 Multi-Epitope Subunit Vaccine Design Against Chikungunya Virus

This repository presents a comprehensive **in silico** pipeline for the design, structural validation, and immunological characterization of a multi-epitope subunit vaccine candidate targeting the *Chikungunya virus (CHIKV)*.

> **Authors**: Abhishek S R, Janani S P  
> Department of Life Science and Bioinformatics, Garden City University, Bangalore, India

---

## 📄 Abstract

Chikungunya virus (CHIKV) is a globally re-emerging arboviral threat with no licensed vaccine. This project uses immunoinformatics, structural bioinformatics, and molecular simulation tools to construct and validate a multi-epitope subunit vaccine targeting the viral structural polyprotein (E1, E2, 6K, E3 - UniProt ID: Q8JUX5). The final construct integrates:

- **T-cell and B-cell epitopes** (MHC-I, MHC-II, Linear and Conformational)
- **β-defensin-3 adjuvant**
- **PADRE sequence** for broad HLA class II coverage
- **Linkers**: EAAAK, AAY, GPGPG, and KK
- **His-tag** for purification

## 🔬 Methodology Overview

### 🎯 Target Protein
- **Accession**: Q8JUX5 (CHIKV structural polyprotein)
- Retrieved from [UniProt](https://www.uniprot.org/)

### 🧩 Epitope Prediction
- **MHC-I & MHC-II epitopes**: Based on immunogenicity, antigenicity, non-toxicity, non-allergenicity
- **Linear and Discontinuous B-cell epitopes**
- **Population coverage** was analyzed for HLA diversity

### 🧱 Vaccine Construction
- Sequence constructed using adjuvant + PADRE + epitopes with appropriate linkers
- Codon-optimized using JCat and cloned in silico into an expression vector

### ⚗️ Bioinformatics Analysis
- **ProtParam**: Solubility, instability index, pI, GRAVY, amino acid composition
- **Psipred**: Secondary structure
- **Robetta + GalaxyRefine**: Tertiary structure prediction and refinement
- **Ramachandran Plot + ERRAT**: Structural validation

### 🧬 Molecular Interactions
- **HADDOCK** docking with:
  - TLR4 (innate immunity)
  - MHC-I (CD8+ T cell response)
  - MHC-II (CD4+ T helper cell activation)

### 🧪 Immune Simulation (C-ImmSim)
- Predicted robust humoral and cellular responses
- Increased memory T and B cells, cytokines, and antibody levels (IgM, IgG1, IgG2)

### 📈 Molecular Dynamics (GROMACS)
- Assessed vaccine stability in a physiological environment

---

## 🧪 Final Construct (Summary)

- **Length**: 291 amino acids
- **MW**: 31.3 kDa
- **pI**: 9.16
- **Instability Index**: 35.42 (stable)
- **GRAVY**: -0.416 (hydrophilic)

---


