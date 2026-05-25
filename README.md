# Rhizobial Symbiotic Gene Compendium

An interactive reference tool for symbiotic genes in *Bradyrhizobium* and related rhizobia.

**🔗 Live tool:** [https://Martin-FABI.github.io/rhizobial-symbiotic-genes/](https://Martin-FABI.github.io/rhizobial-symbiotic-genes/)

---

## Overview

Please take not that this is a work in progress and the author does not take responsibility for any errors at the time of publication.

This resource provides a curated, searchable reference table of **125 symbiotic genes** across eight gene families found in nitrogen-fixing rhizobia, with primary focus on *Bradyrhizobium* spp. Each entry includes the gene function, the organisms it is found in, the maximum reported genomic copy number, conservation status across diazotrophic rhizobia, and hyperlinked literature references.

The tool runs entirely in the browser — no installation or internet connection required after the page loads.

---

## Gene families covered

| Family | Genes | Description |
|--------|-------|-------------|
| **nod** | 23 | Nodulation and Nod factor (LCO) biosynthesis, decoration and export |
| **nol** | 11 | Accessory nodulation genes |
| **noe** | 11 | Nod factor decoration genes |
| **nif** | 18 | Nitrogenase structural and FeMo-cofactor biosynthesis genes |
| **fix** | 19 | Symbiosis-specific nitrogen fixation support genes |
| **hup/hyp** | 19 | Hydrogen uptake hydrogenase and maturation genes |
| **T3SS/nop** | 19 | Type III secretion system and nodulation outer protein effectors |
| **Regulatory/Other** | 5 | σ⁵⁴ factor, two-component regulators, denitrification |

---

## Features

- **Filter by gene family** — click any family button to narrow the table
- **Filter by conservation** — four tiers from Universal to Restricted across diazotrophic rhizobia
- **Search** — full-text search across gene names, functions, organisms and notes
- **Sort** — click any column header to sort
- **Copy number** — maximum number of copies reported in any sequenced genome, with multi-copy genes highlighted
- **56 hyperlinked references** — every entry links to DOI, PubMed and open-access full text where available
- **Standalone** — single HTML file; works offline; no dependencies

---

## Conservation tiers

| Tier | Meaning |
|------|---------|
| ● **Universal** | Present in all diazotrophic rhizobia |
| ● **Common** | Present in most; very few exceptions |
| ◐ **Variable** | Widespread but genus- or clade-restricted |
| ○ **Restricted** | Species- or strain-specific |

---

## Organisms covered

The compendium covers genes documented across the major rhizobial genera:

- *Bradyrhizobium* — primary focus (*B. diazoefficiens*, *B. japonicum*, *B. elkanii*, *B.* sp. BTAi1/ORS278/DOA9)
- *Sinorhizobium* / *Ensifer* — *S. meliloti*, *S. fredii* NGR234
- *Rhizobium* — *R. leguminosarum*, *R. etli*
- *Mesorhizobium* — *M. loti*, *M. huakuii*
- *Azorhizobium* — *A. caulinodans*

---

## Reference strains

Key genomes used for gene annotation and literature curation:

| Strain | Accession | Notable genes |
|--------|-----------|---------------|
| *B. diazoefficiens* USDA110 | GCF_000011365.1 | Full nif/fix/nod; dual hupSL; nopE1/E2 |
| *B. japonicum* USDA6 | GCF_000147775.2 | nod/nif/fix; fixK1/K2; hup |
| *B. elkanii* USDA61 | GCF_000473545.1 | nolL, noeE, dual nopM |
| *S. meliloti* 1021 | GCF_000006965.2 | nodH/nodPQ; fdxN; fixLJ |
| *S. fredii* NGR234 | GCF_000010525.1 | Broad host range; nopL/P/T |
| *R. leguminosarum* Rlv3841 | GCF_000009265.1 | nodX; hup cluster; fnrN |
| *M. loti* MAFF303099 | GCF_000009745.1 | Dual nifA; symbiosis island |
| *A. caulinodans* ORS571 | GCF_000010305.1 | Stem nodulator; nifV; nodS |

---

## Literature

The compendium cites 56 peer-reviewed references covering genome sequences,
gene function studies, and comparative genomics. Key reviews include:

- Dénarié, Debellé & Promé (1996) *Annu. Rev. Biochem.* — Nod factors
- Fischer (1994) *Microbiol. Rev.* — nif/fix gene regulation
- Kaneko et al. (2002) *DNA Res.* — *B. japonicum* USDA110 genome
- Preisig et al. (1996) *J. Bacteriol.* — fixNOQP/cbb3 oxidase
- Hauser et al. (2007) *Mol. Genet. Genomics* — fdxN identification
- Lindström & Mousavi (2020) *Microb. Biotechnol.* — Comprehensive review

Full references with hyperlinks are available in the tool itself.

---

## Intended use

This resource is intended as a:

- **Quick reference** during genome annotation and comparative genomics
- **Teaching resource** for courses on biological nitrogen fixation and plant-microbe interactions
- **Companion tool** for the rhizobial symbiotic gene search and phylogeny pipeline (see [pipeline repository link])

---

## How to use the standalone HTML file

The entire tool is contained in `index.html`. To use it offline:

1. Download `index.html` from this repository
2. Open it in any modern web browser (Chrome, Firefox, Edge, Safari)
3. No internet connection, server or installation required

---

## Citation

If you use this resource in your research, please cite:

> Coetzee MPA. (2025). Rhizobial Symbiotic Gene Compendium. Forestry and Agricultural Biotechnology Institute (FABI), University of Pretoria. Available at: https://Martin-FABI.github.io/rhizobial-symbiotic-genes/
> > Note that the code was developed with Claude AI (Anthropic), and references are in the process of being checked and updated.

---

## Developed by

**Martin Coetzee**
Forestry and Agricultural Biotechnology Institute (FABI)
University of Pretoria, South Africa

Developed in collaboration with **Claude AI** (Anthropic).

---

## Contributing

Errors, missing genes or outdated annotations are welcome as GitHub Issues.
Pull requests with corrections or additions are also welcome.

---

## Licence

This resource is made available for academic and research use.
All literature references remain the copyright of their respective publishers.
